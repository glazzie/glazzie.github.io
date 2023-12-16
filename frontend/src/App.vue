<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { io } from 'socket.io-client'

const socket = io('http://localhost:3000')

</script>

<template>
  <div>
    hej
  </div>
</template>

<style scoped>
</style>
