<template>
  <div>
    <!--
      BREAK POINTの違い
      container: boxを中心に
      container is-fluid: もう少し広い
      is-widescreen: $widescreenまでfull
      is-fullhd: $fullhdまでfull
      (has-text-centered): textを中心に
    -->
    <div class="container is-fluid has-text-centered">
      <div class="notification">
        this continer is <strong>centerd</strong> on desk top
      </div>
    </div>
    <div class="container is-widescreen">
      <div class="notification">
        this container is <strong>fullwidth</strong><em> until</em> the <code>$widescreen</code>breakpoints
      </div>
    </div>
    <div class="container is-fullhd">
      <div class="notification">
        this container is <strong>fullwidth</strong><em> until</em> the <code>$fullhd</code>breakpoints
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
