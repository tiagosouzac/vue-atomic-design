<template>
  <a class="social-link" :href="to" target="_blank">
    <img :src="iconPath" :alt="name" />
  </a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    name: {
      type: String,
      required: true,
    },
    icon: {
      type: String,
      required: true,
    },
    to: {
      type: String,
      required: true,
    },
  },
  computed: {
    iconPath(): string {
      const path = `../../assets/images/icons/${this.icon}`
      return new URL(path, import.meta.url).href
    },
  },
})
</script>

<style lang="scss" scoped>
.social-link {
  width: 3rem;
  height: 3rem;
  border-radius: 3rem;
  background-color: #ff895f;
  transition: transform 0.2s linear;
  display: flex;
  justify-content: center;
  align-items: center;

  &:hover {
    transform: scale(1.1);
  }

  img {
    width: 1.5rem;
    height: 1.5rem;
  }
}
</style>
