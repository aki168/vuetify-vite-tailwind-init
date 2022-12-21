<template>
  <v-app>
    <ChatRoom/>
  </v-app>
</template>

<script>
// import HelloWorld from '@/components/HelloWorld.vue'
import ChatRoom from '@/components/ChatRoom.vue';
export default {
    data: () => ({ drawer: null }),
    components: { ChatRoom }
}
</script>
