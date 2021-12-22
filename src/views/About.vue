<template>
  <div class="about">
    <h1>{{ message }}</h1>
  </div>
</template>

<script lang="ts">
import { Vue } from "vue-property-decorator";

export default class About extends Vue {
  message = "Initial data can be declared as instance properties";
}
</script>
