<template>
  <SocialLink name="Github" to="https://github.com" icon="github.svg" />
  <SocialLink name="Twitter" to="https://twitter.com" icon="twitter.svg" />
  <SocialLink name="Facebook" to="https://facebook.com" icon="facebook.svg" />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  components: { SocialLink },
})
</script>
