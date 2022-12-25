<template>
  <a class="nav-item" :href="to">{{ text }}</a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    text: {
      type: String,
      required: true,
    },
    to: {
      type: String,
      required: true,
    },
  },
})
</script>

<style lang="scss" scoped>
.nav-item {
  color: #293947;
  font-size: 1.3rem;
  text-decoration: none;
}
</style>
