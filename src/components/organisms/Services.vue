<template>
  <div class="services">
    <Service
      title="Front end"
      content="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque est illum aliquam ducimus praesentium tempora aut, quibusdam, voluptatum dolor reiciendis sapiente! Quae assumenda voluptates hic expedita omnis optio facere adipisci!"
    />

    <Service
      title="Back end"
      content="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque est illum aliquam ducimus praesentium tempora aut, quibusdam, voluptatum dolor reiciendis sapiente! Quae assumenda voluptates hic expedita omnis optio facere adipisci!"
    />

    <Service
      title="Manutenção"
      content="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eaque est illum aliquam ducimus praesentium tempora aut, quibusdam, voluptatum dolor reiciendis sapiente! Quae assumenda voluptates hic expedita omnis optio facere adipisci!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service },
})
</script>

<style lang="scss" scoped>
.services {
  display: flex;
  gap: 5rem;
}
</style>
