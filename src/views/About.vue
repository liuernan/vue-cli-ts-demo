<template>
  <div class="about">
    <h1>{{ message }}</h1>
    <button @click="handleClick">click</button>
  </div>
</template>

<script lang="ts">
import { Vue } from "vue-property-decorator";

export default class About extends Vue {
  message = "hi";

  handleClick(e: MouseEvent): void {
    console.log(e.target);
    window.alert("function 是这样用的");
  }
}
</script>
