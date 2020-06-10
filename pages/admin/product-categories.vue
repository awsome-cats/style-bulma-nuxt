<template>
  <div>
    <section class="section no-top-pad">
      <h5 class="title is-5">
        プロダクトカテゴリー
      </h5>
      <!-- columns start -->
      <div class="columns">
        <!-- 1/3  column1 -->
        <div class="column is-one-third">
          <!-- field start -->
          <div class="field">
            <label class="label">
              <div class="control">
                <input type="text" name="category" class="input">
              </div>
            </label>
          </div>
          <!-- field end -->
          <!-- field start -->
          <div class="field">
            <div class="control">
              <button class="button is-primary">
                作成
              </button>
            </div>
          </div>
          <!-- field end -->
        </div>
        <!-- column2 start -->
        <div class="column">
          <tabel class="table is-striped is-fullwidth">
            <thead>
              <tr>
                <th>#</th>
                <th>カテゴリー</th>
                <th>&nbsp;</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th>1</th>
                <td><a href="">cat スナック</a></td>

                <td><a href="" /></td>
              </tr>
              <tr>
                <th>2</th>
                <td><a href="">cat 缶</a></td>
                <td><a href="" /></td>
              </tr>
            </tbody>
          </tabel>
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
