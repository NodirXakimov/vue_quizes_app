<script setup>
    import Question from '../components/Question.vue' 
    import QuizHeader from '../components/QuizHeader.vue' 
    import {useRoute} from 'vue-router' 

    const route = useRoute()

</script>

<template>
    <div>
        <QuizHeader />
        <div>
            <Question />
        </div>
    </div>
</template>