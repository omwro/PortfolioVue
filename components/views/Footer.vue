<template>
    <footer id="footer" class="bg-primary-block-light dark:bg-primary-block-dark italic text-[0.9rem] text-center overflow-hidden px-0 py-2">
        <div class="whitespace-nowrap px-2 py-0">
            &copy; 1999 - {{ getCurrentYear() }} Omer Erdem All Rights Reserved
        </div>
    </footer>
</template>

<script setup>
import { getCurrentYear } from "../../composables/useDate";
</script>

<script>
export default {
    name: "Footer"
};
</script>