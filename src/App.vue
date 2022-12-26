<template>
  <Header />
  <Presentation />
  <Services />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation, Services } from '@/components/organisms'

export default defineComponent({
  components: { Header, Presentation, Services },
})
</script>
