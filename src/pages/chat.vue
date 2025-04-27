<template>
<v-container class="chat-page fill-height pa-0" fluid>    
  <Chat />
  </v-container>
</template>

  <script setup lang="ts">
  import Chat from '@/components/Chat.vue';
  </script>

  <style scoped>
  .chat-page {
    width: 100%;
  }
  </style>
