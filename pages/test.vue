<template>
  <div>
    <!-- Header -->
    <header class="navbar is-info">
      <div class="navbar-brand">
        <span class="navbar-item"><span class="fa fa-language" />sns</span>
      </div>
      <div class="navbar-end">
        <div class="navbar-item">
          <div class="field has-addons">
            <div class="control">
              <input type="text" class="input" name="サーチ" placeholder="サーチ...">
            </div>
            <div class="control">
              <a href="" class="button is-info">
                <i class="fa fa-search" />検索
              </a>
            </div>
          </div>
        </div>
        <div class="navbar-item">
          <a href="#" class="fa fa-user">ログイン</a>
        </div>
      </div>
    </header>
    <!--
      style
      hero: ヒーローエリア・ヒーローバナー
      is-info: collor
      i-bold: グラデーション
      hero-body/hero-head/hero-foot
      container: 水平にセンタリング
      -->
    <div class="hero is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Thank You
          </h1>
          <h2 class="subtitle">
            @kkmaster
          </h2>
        </div>
      </div>
    </div>
    <!--
      level:
      level-left/level-right
      level-item
      tabs:内包されたulリストがタブとして表示される
      is-active: 現在選択中:変化はJavaScriptで行う
    -->
    <section class="level">
      <div class="level-left" />
      <div class="level-right">
        <div class="level-item tabs">
          <ul>
            <li class="is-active">
              <a href="#">最近のtweet</a>
            </li>
            <li><a href="">過去のtweet</a></li>
            <li><a href="">コメント</a></li>
          </ul>
        </div>
      </div>
      <div class="level-right">
        <div class="level-item">
          <a href="#" class="button is-greylight">フォロー</a>
        </div>
      </div>
    </section>
    <!-- Main -->
    <!--
      colums
      colum
      box: 影付き/角丸/背景色白/境界線
      menu: 垂直型navgation
      menu/menu-label/menu-list
    -->
    <main class="columns">
      <div class="submenu column is-3">
        <aside class="box menu">
          <p class="menu-label">
            おすすめの一言
          </p>
          <ul class="menu-list">
            <li>
              <a href="#">株式会社<small>@kenny</small>
              </a>
            </li>
            <li>
              <a href="#">kenny制作</a><small>@kennyInc</small>
            </li>
            <li>
              <a href="#">オフィス</a><small>@@kenn</small>
            </li>
          </ul>
          <p class="menu-label">
            キーワード
          </p>
          <ul class="menu-list">
            <li><a href="">システム開発</a></li>
            <li><a href="#" class="is-active">技術教育</a></li>
            <ul>
              <li><a href="">一社研修</a></li>
              <li><a href="">定期開催コース</a></li>
            </ul>
            <li><a href="">ソフトウェアテスティング</a></li>
          </ul>
        </aside>
      </div>
      <!-- Right Side -->
      <!--
        medea: ユーザー同士の交流を主軸としたWebサイト等で多く見られるデザイン
        ネストで階層的な表現ができる
        media-left: mediaの中で使う userのアイコンを表す
        media-content: mediaの中の本文
        image: imgを内包する
      -->
      <div class="column">
        <article class="box media">
          <figure class="media-left">
            <p class="image is-64×64">
              <img src="https://placehold.it/128x128" alt="画像">
            </p>
          </figure>

          <div class="media-content">
            <div class="content">
              <p>
                <strong>Kenny</strong>
                <br>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque repellat asperiores non porro earum deserunt odit, distinctio ipsa voluptatum ratione atque voluptatibus. Ab natus quas quidem repudiandae magni ratione nostrum!
                <br>
                <small><a>Like</a><a>Replay</a>. 3 hrs</small>
              </p>
            </div>

            <article class="media">
              <figure class="media-left">
                <p class="image is-48x48">
                  <img src="https://placehold.it/48x48" alt="">
                </p>
              </figure>
              <div class="media-content">
                <div class="content">
                  <p>
                    <strong>neel</strong>
                    <br>
                    コメントコメントコメントコメント<br>
                    <small><a>Like</a>・Replay</small>
                  </p>
                </div>
                <article class="media">
                  リプライLorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat voluptas modi sequi. Sequi dolor sunt quibusdam! Sint, debitis. Unde nihil dolore quasi incidunt iure fuga impedit cum quos culpa hic.
                </article>
                <article class="media">
                  リプライLorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae, dolore? Deserunt minima saepe modi unde a illum. Culpa incidunt deleniti tempore ut modi rerum quo eos excepturi assumenda, recusandae facilis.
                </article>
              </div>
            </article>
          </div>
        </article>

        <article class="box media">
          <figure class="media-left">
            <p class="image is-48x48">
              <img src="https://placehold.it/96x96" alt="">
            </p>
          </figure>
          <div class="media-content">
            <div class="content">
              <p>
                <strong>Kenny</strong><br>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Explicabo veniam at perferendis a, aliquam officia facilis, animi, nesciunt odit debitis laboriosam? Autem, cumque perferendis? Quibusdam veniam iste officiis sunt ipsam?
                <small><a href="#">Like</a> Reply 2 hrs</small>
              </p>
            </div>
          </div>
        </article>
      </div>
    </main>
    <footer class="footer">
      <div class="container">
        <div class="content has-text-centered">
          2020 @kenny
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

export default {
  layout: 'test',
  components: {
  }
}
</script>

<style>
main {
    background-color: #eeeeee;
  }
</style>
