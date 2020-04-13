<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>GGGGG</h2>
  </div>
</template>

<script lang="ts">
import { ref } from "@vue/composition-api";

export default {
  name: "HelloWorld",

  setup() {
    // const state = reactive({
    //   count: 0,
    //   double: computed(() => state.count * 2)
    // });
    const msg = ref("hello marty...");

    // const increment = () => state.count++;

    return {
      msg
    };
  }
};
</script>
