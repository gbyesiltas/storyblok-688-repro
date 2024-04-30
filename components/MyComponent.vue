<script setup lang="ts">
defineProps<{
    name: string;
    age: number;
    isSomething: boolean;
}>();
</script>

<template>
    <div>
        {{ name }}
        {{ age }}
        {{ isSomething }}
    </div>
</template>