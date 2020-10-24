<template lang="pug">
  div.container
    div.container_list.top

    div.container_list.hamon
      h2 波紋
      p 
        | 私たち公立はこだて未来大学情報デザインコースは、情報社会で豊かに生きるためのデザイン理論や<br>表現方法に加え、情報科学屋認知科学の最新の理論と実践を学んできました。<br><br>
        | これまでの集大成として「波紋」をテーマとした社会に一石を投じる<br>新たなデザインの可能性を提示する展覧会を開催します。<br><br>
        | 本展覧会が社会へ波紋を呼び、形を変えながら新たな波を起こし、<br>起こし続けるきっかけとなることを期待しています。
    div.container_list.introduction
      h2 研究・活動の紹介
      p 
        | 今年度の卒業展覧会は新型コロナウイルスの感染拡大防止の観点から、<br>対面形式ではなくオンラインでの開催といたします。<br><br>
        | そのため、研究活動や作品紹介は当サイトにて常設展示いたします。<br>研究者本人からのコメントや動画での紹介も行っております。<br>是非ごゆっくりご覧ください。<br><br>
    div.container_list.session
      h2 オンラインセッション
      p
        | 出展者と来場者の皆様との対話の場は日時を設定の上、実施いたします。（詳細はこちらをご覧ください）<br><br>
        | 例年と異なる形式となりますが、より多くの方々にご来場いただけることを楽しみにしております。
      
</template>

<script>
import Card from '~/components/Card.vue'
import Footer from '~/components/Footer.vue'
import Header from '~/components/Header.vue'
import Title from '~/components/Title.vue'

export default {
  components: {
    Header,
  }
}
</script>

<style lang="sass">

@media screen and (max-width: 700px) //スマホ
  .container
    

@media screen and (min-width: 701px) //パソコン
  .container
    align-items: center;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
    min-height: 100vh;
    width: 100%;
    .container_list
      color: #fff;
      padding: 5vw 20%;
      text-align: center;
      width: 100%;
      h2
        font-size: 32px;
        margin: 0 0 4vw 0;
      p
        font-feature-settings: "palt" 1;
        font-size: 18px;
        line-height: 1.8;
        margin: 24px auto;
    .top
      background: no-repeat center/80% url('/background.jpg');
      height: 80vh;
    .hamon
      background-color: #417BBF;
    .introduction
      background-color: #E94917;
    .session
      background-color: #6AB82C;

</style>
