<template>
    <section>
    <div class="panel">
    <q-list bordered class="rounded-borders" style="max-width: 950px">
      <q-item-label header style="font-size: 36px;">Yardım Paneli</q-item-label>

      <q-item clickable v-ripple style="background-color: #FFCCCB; font-size: 36px;">
        <q-item-section avatar>
          <q-avatar>
            <img src="https://e7.pngegg.com/pngimages/119/501/png-clipart-computer-icons-user-woman-woman-hat-people-thumbnail.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label lines="1">Aslı Ergün</q-item-label>
          <q-item-label caption lines="2" style="font-size: 20px;">
            <span class="text-weight-bold">ANKARA-ÇANKAYA</span>
            Hacıoğlu mah. 1190.Sk Yeşim Apt. No :22
          </q-item-label>
        </q-item-section>

        <q-item-section side top>
          5 dakika önce
        </q-item-section>
      </q-item>

      <q-separator inset="item" />

      <q-item clickable v-ripple style="background-color: #90EE90; font-size: 36px;">
        <q-item-section avatar>
          <q-avatar>
            <img src="https://w7.pngwing.com/pngs/188/501/png-transparent-computer-icons-anonymous-anonymity-anonymous-face-monochrome-head-thumbnail.png">
          </q-avatar>
        </q-item-section>

        <q-item-section>
          <q-item-label lines="1">Halit Sağlam</q-item-label>
          <q-item-label caption lines="2" style="font-size: 20px;">
            <span class="text-weight-bold">İSTANBUL-BAĞCILAR</span>
            Güngören Mah. Atlılar Sk. Kara Apt. No:35
          </q-item-label>
        </q-item-section>

        <q-item-section side top>
          9 dakika önce
        </q-item-section>
      </q-item>
    </q-list>
  </div>
  </section>
</template>

<script>
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'YardimPanel',
  setup () {
    return {
      password: ref(''),
      email: ref('')
    }
  }
})
</script>
