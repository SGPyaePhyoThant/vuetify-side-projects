<template>
<div class="home text-center">
    <h3>諦めないで準備して続けること大切</h3>
    <div class="purple darken-2 white--text text-center">
      横浜市（よこはまし）は、神奈川県東部に位置する市。
      神奈川県の県庁所在地及び人口が最多の市で、政令指定都市である。
      日本有数の港湾都市・商工業都市でもある。
    </div>
    <br><br>

    <v-btn
  color="primary"
  elevation="24"
>横浜へ</v-btn>
 <br><br>
<v-btn
  color="primary"
  elevation="24"
  plain
>横浜へ</v-btn>
 <br><br>
 <v-btn
  color="primary"
  elevation="24"
  text
  top
>横浜へ</v-btn>
<br><br>
<v-btn  class="pink white--text">
 <v-icon left>mdi-email </v-icon>メール送る
</v-btn>
<br><br>
<v-btn small  class="pink white--text" elevation="24">
 <v-icon left>mdi mdi-airplane</v-icon>飛行機で日本へ行く
</v-btn>
<br><br>
<v-btn depressed  class="primary" fab elevation="24">
 <v-icon>mdi mdi-airplane</v-icon>
</v-btn>
    
</div>
</template>

<script>

  export default {
    name: 'Home',

    components: {
    },
  }
</script>
