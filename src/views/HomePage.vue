<script setup>
import HelloWorld from "@/components/HelloWorld.vue";

const handleClick = () => {
  AMessage.info('hello isboyjc, click mini AButton!')
};

</script>
<template>
  <div>hello isboyjc, This is toolsdog home page!</div>
  <a-space>
    <a-button type="primary" @click="handleClick">Primary</a-button>
    <a-button>Secondary</a-button>
    <a-button type="dashed">Dashed</a-button>
    <a-button type="outline">Outline</a-button>
    <a-button type="text">Text</a-button>
    <span><icon-ep-alarm-clock class=""/> </span>
  </a-space>
  <HelloWorld />
</template>
<style scoped></style>
