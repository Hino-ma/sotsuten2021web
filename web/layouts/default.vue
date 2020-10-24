<template lang="pug">
  div#app
    div#header
      div.link
        nuxt-link.link_top(to="/") 卒業研究展覧会2021
      div.link
        div.link_listIntermal
          nuxt-link(to="/") 研究紹介
          nuxt-link(to="/") オンラインセッション
          nuxt-link(to="/contact") お問い合わせ
        div.link_listExternal
          a(href="#" rel="noopener noreferrer" target="_blank")
          a(href="#" rel="noopener noreferrer" target="_blank")     
    div#body
      Nuxt
    div#footer
      div.footer_funLogo 公立はこだて未来大学
      div.footer_copyRight ©公立はこだて未来大学　情報デザインコース

</template>

<style lang="sass">
html
  box-sizing: border-box;
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;


@media screen and (max-width: 700px) //スマホ
  #app

@media screen and (min-width: 701px) //パソコン
  #app
    #header
      align-items: center;
      box-shadow: 0 4px 8px #eee;
      display: flex;
      height: 60px;
      justify-content: space-between;
      width: 100%;
      a
        text-decoration: none;
      .link_top
        color: #333;
        font-size: 24pt;
        font-weight: 600;
        padding: 0 0 0 24px;
      .link_listIntermal
        padding: 0 24px 0 0;
        a
          color: #555;
          font-size: 16pt;
          font-weight: 600;
          padding: 0 0 0 16px;
    #footer
      align-items: center;
      background-color: #545E65;
      color: #fff;
      display: flex;
      height: 80px;
      justify-content: space-between;
      width: 100%;
      .footer_funLogo
        font-size: 18px;
        padding: 0 0 0 48px;
      .footer_copyRight
        font-size: 14px;
        padding: 0 48px 0 0;


</style>
