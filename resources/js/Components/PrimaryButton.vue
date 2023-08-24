<script setup>
defineProps({
    type: {
        type: String,
        default: "submit",
    },
});
</script>

<template>
    <button
        :type="type"
        class="bg-blue-500 hover:bg-blue-700 w-full rounded-lg p-1.5 text-white text-lg font-extrabold"
    >
        <slot />
    </button>
</template>
