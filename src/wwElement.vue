<template>
  <button @click="testClick">Click Me</button>
</template>

<script setup>
    const testClick = () => {
        console.log('testClick');
    }
</script>