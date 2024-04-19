<template>

   
    <div>The page with time {{ timer }}</div>
<slot>Default</slot>

</template>

<script setup>
import { ref } from 'vue'

const timer = ref(0)
setInterval(() => timer.value++ , 1000)
</script>