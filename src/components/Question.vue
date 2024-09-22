<template>
    <div>{{ quiz.questions[0].question }}</div>
</template>

<script setup>
defineProps({
    quiz: Object
})
</script>