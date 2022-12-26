<template>
  <header class="header">
    <Logo />
    <NavBar />
    <SearchForm />
  </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from '@/components/atoms'
import { NavBar, SearchForm } from '@/components/molecules'

export default defineComponent({
  components: { Logo, NavBar, SearchForm },
})
</script>

<style lang="scss" scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;

  .logo {
    max-width: 160px;
  }
}
</style>
