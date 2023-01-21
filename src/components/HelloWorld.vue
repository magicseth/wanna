<script setup lang="ts">
import VueWriter from "vue-writer";
defineProps<{
  msg: string;
}>();
</script>

<template>
<div class="greetings">
  <h1 class="green">Wanna chat with an AI?</h1>
  <h3>
    I'm your <b style="font-weight:bold">AI </b>
    <VueWriter style="display: inline" :array="[
      'coach',
      'sounding board',
      'mentor',
      'muse',
      'cowriter',
      'listener',
      'rubber ducky',
    ]" /><br /><br />
    ☏
    <div>
      Call the AI:
      <a href="tel:1-910-727-4468">1-910-727-4468 <span style="font-size: 2em"></span></a>
    </div>☏
  </h3>
</div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {

  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
