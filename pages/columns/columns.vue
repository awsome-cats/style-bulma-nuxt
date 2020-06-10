<template>
  <div>
    <div class="columns">
      <div class="column left-top-column">
        <p class="subtitle">
          User Info
        </p>
        <full-width-user />
        <for-fifth />
        <two-fifth />
      </div>
    </div>
    <div class="columns">
      <div class="column left-top-column">
        <p class="subtitle">
          登録情報
        </p>
        <user-addresses />
        <user-addresses />
        <user-addresses />
      </div>
      <div class="column right-top-column">
        <p class="subtitle">
          目標達成
        </p>

        <user-purpose />
        <user-purpose />
        <user-purpose />
      </div>
    </div>
  </div>
</template>

<script>
import UserAddresses from '@/components/columns/UserAddresses'
import UserPurpose from '@/components/columns/UserPurpose'
import FullWidthUser from '@/components/columns/FullWidthUser'
import ForFifth from '@/components/columns/ForFifth'
import TwoFifth from '@/components/columns/TwoFifth'
export default {
  components: { UserAddresses, UserPurpose, FullWidthUser, ForFifth, TwoFifth }
}
</script>

<style scoped>

.left-top-column {
  background: rgb(214, 219, 214);
  height:100%;
}
.left-top-inner-column {
  background: rgb(211, 119, 119);
}

.right-top-column {
  background: rgb(214, 219, 214);
}

/* .columns {
  margin:5px;
} */
</style>
