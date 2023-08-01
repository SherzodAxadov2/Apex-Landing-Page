<template>
  <div class="headerMain">
    <Header />
    <StartChatting />
    <nextChatting />
    <peredChatting />
    <ParentChatting />
    <navbar />
    <background />
  </div>
</template>

<script lang="js">
import Header from './components/Header.vue';
import StartChatting from './components/StartChatting.vue';
import nextChatting from './components/nextChatting.vue';
import peredChatting from './components/peredChatting.vue';
import ParentChatting from './components/ParentChatting.vue';
import navbar from './components/navbar.vue';
import background from './components/background.vue';

export default {
  components: { Header, StartChatting, nextChatting, ParentChatting, peredChatting, ParentChatting, navbar, background }
}
</script>
