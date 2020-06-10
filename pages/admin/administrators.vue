<template>
  <div>
    <section class="section no-top-pad">
      <h5 class="title is-5">
        管理者ページ
      </h5>
      <div class="columns">
        <div class="column is-one-third">
          <!-- field start -->
          <div class="field">
            <label class="label">名前</label>
            <div class="control">
              <input type="text" name="name" class="input">
            </div>
          </div>
          <!-- field end -->
          <div class="field">
            <label class="label">Email</label>
            <div class="control">
              <input type="email" name="email" class="input">
            </div>
          </div>
          <div class="field">
            <label class="label">パスワード</label>
            <div class="control">
              <input type="password" name="password" class="input">
            </div>
          </div>
          <div class="field">
            <div class="control">
              <button type="submit" class="button is-primary">
                作成
              </button>
            </div>
          </div>
        </div>
        <div class="column">
          <table class="table is-striped is-fullwidth">
            <thead>
              <tr>
                <th>#</th>
                <th>管理者</th>
                <th>&nbsp;</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th>1</th>
                <th>マネージャー</th>
                <td><a href="#">削除</a></td>
              </tr>
              <tr>
                <th>2</th>
                <th>チームリーダー</th>
                <td><a href="#">削除</a></td>
              </tr>
              <tr>
                <th>3</th>
                <td>社員</td>
                <td><a href="#">削除</a></td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
