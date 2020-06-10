<template>
  <nav class="navbar is-primary section">
    <!-- navbar-brand start -->
    <div class="navbar-brand">
      <nuxt-link to="/test">
        <p class="image is-64x64">
          <img src="https://placehold.it/64x64" alt="">
        </p>
      </nuxt-link>

      <div class="navbar-burger burger" data-target="top-mene">
        <span />
        <span />
        <span />
      </div>
    </div>
    <!-- navbar-brand end -->
    <div id="top-mene" class="navbar-menu">
      <!-- navbar start start -->
      <div class="navbar-start">
        <nuxt-link class="navbar-item" to="/">
          Home
        </nuxt-link>
        <div class="navbar-item has-dropdown is-hoverable">
          <a href="#" class="navbar-link ">Admin</a>
          <div class="navbar-dropdown">
            <nuxt-link class="navbar-item" to="/admin/product-list">
              プロダクト
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/admin/product-categories">
              プロダクトカテゴリー
            </nuxt-link>
            <a href="#" class="navbar-item">オーダーズ</a>
            <a href="#" class="navbar-item">カスタマーズ</a>
            <nuxt-link class="navbar-item" to="/admin/administrators">
              管理者ページ
            </nuxt-link>
            <nuxt-link class="navbar-item" to="/admin/user-groups">
              ユーザーグループ
            </nuxt-link>
          </div>
        </div>
      </div>
      <div class="navbar-item has-dropdown is-hoverable">
        <a href="#" class="navbar-link ">カラム</a>
        <div class="navbar-dropdown">
          <nuxt-link to="/columns/columns">
            カラム
          </nuxt-link>
          <nuxt-link to="/hero">
            Hero
          </nuxt-link>
        </div>
      </div>
      <!-- navbar start end -->
      <!-- navbar end start -->
      <!--
        is-active: 濃い色で表す
        has-dropdown/is-hoverable: 組み合わせがいい
      -->
      <div class="navbar-end">
        <div class="navbar-item has-dropdown is-hoverable">
          <a href="#" class="navbar-link">
            こんにちは、user さん
          </a>
          <div class="navbar-dropdown">
            <nuxt-link class="navbar-item" to="/user-profile">
              プロフィール
            </nuxt-link>
            <nuxt-link class="navbar-item" to="user-pwd-change">
              パスワードの変更
            </nuxt-link>
            <a class="navbar-item">ログアウト</a>
          </div>
        </div>
        <div class="navbar-item">
          こんにちは、userさん
        </div>
        <div class="navbar-item">
          <div class="field is-grouped is-grouped-multiline">
            <p class="control">
              <nuxt-link class="button" to="/cart">
                <span class="icon is-small">
                  <i class="fa fa-shopping-cart" />
                </span>
                <span>&bullet; 0 item(¥0/00)</span>
              </nuxt-link>
            </p>
            <p class="control">
              <nuxt-link class="button is-primary" to="/login">
                <span class="icon is-small">
                  <i class="fa fa-unlock-alt" />
                </span>
                <span>ログイン</span>
              </nuxt-link>
            </p>
            <p class="control">
              <nuxt-link class="button is-info" to="/signup">
                <span class="icon is-small">
                  <i class="fa fa-user-o" />
                  <span>登録</span>
                </span>
              </nuxt-link>
            </p>
          </div>
        </div>
      </div>
      <!-- navbar end end -->
    </div>
  </nav>
</template>

<script>
export default {
  data () {
    return {

    }
  },
  methods: {
  }

}
</script>

<style>

</style>
