<template>
  <section class="section no-top-pad">
    <h5 class="title is-5">
      ユーザー作成フォーム
    </h5>
    <div class="columns">
      <!-- 1/3 -->
      <div class="column is-one-third">
        <form action="">
          <!-- field start -->
          <div class="field">
            <label class="label">新しいユーザー</label>
            <div class="control">
              <input type="text" name="usergroup" class="input">
            </div>
          </div>
          <!-- field end -->
          <!-- field start -->
          <div class="field">
            <div class="control">
              <button class="button is-primary">
                新規作成
              </button>
            </div>
          </div>
        </form>
      </div>
      <!-- field end -->
      <div class="column">
        <table class="table is-striped is-fullwidth">
          <thead>
            <tr>
              <th>#</th>
              <th>ユーザーグループ</th>
              <th>&nbsp;</th>
            </tr>
          </thead>
        </table>
        <tbody>
          <tr>
            <th>1</th>
            <th><a href="#">管理者</a></th>
            <th><a href=""><span class="icon has-text-danger"><i class="fa fa-lg fa-times-circle" /></span></a></th>
          </tr>
        </tbody>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: 'admin'
}
</script>

<style>

</style>
