<template>
  <div>
    <section class="section no-top-pad">
      <h5 class="title is-5">
        ログイン
      </h5><hr>
      <div class="columns is-centered is-mobile">
        <div class="column is-full-tablet is-half-desktop is-full-mobile">
          <!--
            is-full-mobile: 画面に合わせてついてくる
            is-half-desktop:1024pxで画面の半分になる/それ以下になると画面についていく
            is-full-tablet: 970px以下になると画面についてくる
          -->
          <!--   is-full-tablet -->
          <form>
            <div class="field">
              <label class="label">Email</label>
              <input type="text" name="email" class="input">
              <p class="help is-danger" />
            </div>
            <div class="field">
              <label class="label">パスワード</label>
              <!-- control: formのスタイルの調整に使うらしい -->
              <div class="control">
                <input type="text" name="password" class="input">
                <p class="help is-danger" />
              </div>
            </div>
            <div class="field">
              <div class="control">
                <button class="button is-primary">
                  送信
                </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  layout: 'admin'
}
</script>

<style>

</style>
