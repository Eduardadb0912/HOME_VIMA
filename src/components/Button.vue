<script setup>
import { ref } from 'vue'
</script>

<template>
    <button class="button">Ver Agora &#8594;</button>
</template>

<style scoped>
.button{
    background-color: #00474f;
    border: none;
    cursor: pointer;
    padding: 0.5rem 2.5rem;
    border-radius: 9999px;
    color: #fff;
    font-size: 2vh; 
    transition: all 0.2s;
}

.button:hover{
    background-color: #34e7f8;
}
</style>
