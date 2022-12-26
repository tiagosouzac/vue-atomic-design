<template>
  <div class="presentation">
    <SocialNetworks />

    <img
      class="banner"
      src="@/assets/images/presentation.svg"
      alt="Apresentação"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialNetworks } from '@/components/molecules'

export default defineComponent({
  components: { SocialNetworks },
})
</script>

<style lang="scss" scoped>
.presentation {
  display: flex;
  align-items: center;
  position: relative;

  .banner {
    width: 80%;
    margin: 0 auto;
  }
}
</style>
