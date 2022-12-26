<template>
  <Container>
    <Header />
    <Presentation />
    <Services />
  </Container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation, Services } from '@/components/organisms'
import { Container } from '@/components/bosons'

export default defineComponent({
  components: { Header, Presentation, Services, Container },
})
</script>
