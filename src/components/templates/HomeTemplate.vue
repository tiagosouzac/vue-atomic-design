<template>
  <Container class="home-template">
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
  components: { Container, Header, Presentation, Services },
})
</script>

<style lang="scss" scoped>
.home-template {
  margin: 5rem auto;
  display: flex;
  flex-direction: column;
  gap: 5rem;
}
</style>
