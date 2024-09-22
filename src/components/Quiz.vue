<template>
    <h1>{{ quiz.title }}</h1>
    <Question :quiz="quiz" v-if="quiz"></Question>
</template>

<script setup>
import Question from './components/Question.vue'

const step = ref(0)

defineProps({
    quiz: Object
})
</script>