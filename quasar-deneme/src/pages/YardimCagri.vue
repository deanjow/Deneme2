<template>
    <p style="font-size: 20px; position: relative; left:15px; top:90px;"> YARDIM ÇAĞRISI İÇİN BUTONA BASINIZ</p>
    <q-btn class="glossy" rounded color="deep-orange" label="ACİL YARDIM" />
</template>

<script>
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'YardimCagri',
  setup () {
    return {
      password: ref(''),
      email: ref('')
    }
  }
})
</script>
