<template>
  <div class="back">
    <img class="icon" src="../assets/icon_login.png">
    <div class="temp1">
      <div class="input-container">
        <input placeholder="请输入您的手机号">
      </div>
      <div class="input-container" >
        <input placeholder="请输入验证码">
        <button >获取验证码</button>
      </div>
      <button class="register">注册下载</button>
    </div>
    <div class="temp2">
      <p>"零"门槛话费充值10%机会享免单</p>
    </div>
  </div>
</template>

<script>
  export default {
    name: "login"
  }
</script>

<style lang="stylus" scoped>
  .back
    width 100vw
    min-height 100vh
    overflow hidden
    background #E80808 url("../assets/back_login.png") no-repeat
    background-position 0 0
    background-attachment fixed
    background-size 100% 100%
    box-sizing border-box
    display flex
    flex-direction column
    align-items center

    .icon
      margin-top 30px
      width 80%
      height auto

    .temp1
      width 90vw
      margin-top 20px
      background url("../assets/temp_login1.png") no-repeat
      background-position 0
      background-size cover
      display flex
      flex-direction column
      align-items center
      justify-content center

      .input-container
        background-color white
        width 90%
        min-height 40px
        padding 0 10px
        box-sizing border-box
        border-radius 8px
        display flex
        align-items center
        justify-content space-between
        margin-top 10px

        button
          color #E80808
          font-size 14px
          background-color transparent
      .input-container&::nth-child(1)
        margin-top 0

      .register
        height 40px
        border-radius 25px
        width 90%
        background-color #E80808
        color white
        line-height 40px
        text-align center
        margin 20px auto

    .temp2
      width 90vw
      height 250px
      background url("../assets/temp_login2.png") no-repeat
      background-position 0
      background-size 100% 100%
      margin 20px auto
      display flex
      flex-direction column
      align-items center

      p
        color #E80808
        margin-top 18px
        font-size 20px
        font-weight bold

</style>
