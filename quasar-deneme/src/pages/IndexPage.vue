<template>
  <!DOCTYPE html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Navbar</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="styles.css">
        <link href="https://fonts.googleapis.com/css?family=Montserrat:500&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <p class="logo">DEPREM YARDIM PLATFORMU</p>
            <nav>
                <ul class="nav__links">
                    <li><a href="#">Ana Sayfa</a></li>
                    <li><a href="#">Nasıl Kullanılır</a></li>
                    <li><a href="#">Hakkımızda</a></li>
                </ul>
            </nav>
            <a class="cta" href="#">Kayıt Ol</a>
            <p class="menu cta">Menu</p>
        </header>
        <div class="overlay">
            <a class="close">&times;</a>
            <div class="overlay__content">
                <a href="#">Services</a>
                <a href="#">Projects</a>
                <a href="#">About</a>
            </div>
        </div>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <section>
      <div class="login">
        <div class ="forms">
      <h3 class="giris"> Kullanıcı Girişi</h3>
      <div class="inputbox">
        <q-input
        filled
        v-model="id"
        label="T.C No"
        mask="###########"
        unmasked-value
        hint="T.C No: 12345678901"
        class = "tc"
      />
      </div>
      <div class="inputbox">
      <q-input v-model="password" filled type="password" hint="Şifre" class = "sifre" />
      </div>
      <div class="forget">
      <p class="label1"> Hesabınız yoksa <a href="" class="reg">Kayıt Ol</a></p>
      </div>
      <q-btn color="primary" label="GİRİŞ YAP" class="girisbtn" />
    </div>
     </div>
    </section>
    </body>
</template>

<script>
import { defineComponent, ref } from 'vue'

export default defineComponent({
  name: 'IndexPage',
  setup () {
    return {
      password: ref(''),
      email: ref('')
    }
  }
})
</script>
