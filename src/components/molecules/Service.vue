<template>
  <div class="service">
    <h2>{{ title }}</h2>
    <p>{{ content }}</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    title: {
      type: String,
      required: true,
    },
    content: {
      type: String,
      required: true,
    },
  },
})
</script>

<style lang="scss" scoped>
.service {
  h2 {
    margin-bottom: 0.8rem;
    color: #935e92;
    font-weight: bold;
  }

  p {
    color: #293947;
    line-height: 1.5;
  }
}
</style>
