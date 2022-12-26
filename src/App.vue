<template>
  <Header />
  <Presentation />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation } from '@/components/organisms'

export default defineComponent({
  components: { Header, Presentation },
})
</script>
