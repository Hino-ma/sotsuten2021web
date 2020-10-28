<template lang="pug">
  div.container
    div.container_list.top

    div.container_list.hamon
      h2 波紋
      p
        | 私たち公立はこだて未来大学情報デザインコースは、情報社会で豊かに生きるためのデザイン理論や<br>表現方法に加え、情報科学屋認知科学の最新の理論と実践を学んできました。<br><br>
        | これまでの集大成として「波紋」をテーマとした社会に一石を投じる<br>新たなデザインの可能性を提示する展覧会を開催します。<br><br>
        | 本展覧会が社会へ波紋を呼び、形を変えながら新たな波を起こし、<br>起こし続けるきっかけとなることを期待しています。

</template>

<script>
import Card from '~/components/Card.vue'
import Footer from '~/components/Footer.vue'
import Title from '~/components/Title.vue'
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
