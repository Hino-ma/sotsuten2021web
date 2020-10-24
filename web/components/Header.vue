<template lang="pug">
div.header
  div.link
    nuxt-link.link_top(to="/") 卒業研究展覧会2021
    div.link_listIntermal
      nuxt-link(to="/") 研究紹介
      nuxt-link(to="/") オンラインセッション
      nuxt-link(to="/") お問い合わせ
    div.link_listExternal
      a(href="#" rel="noopener noreferrer" target="_blank")
      a(href="#" rel="noopener noreferrer" target="_blank")
</template>


<script>
export default {
    
}
</script>


<style lang="sass" scoped>
@media screen and (max-width: 700px) //スマホ
  .header
    

@media screen and (min-width: 701px) //パソコン
  .header
    box-shadow: 0 0px 5px #ccc;
    width: 100vw;


</style>