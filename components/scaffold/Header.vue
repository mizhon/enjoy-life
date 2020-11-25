<template>
  <div class="main-header">
    <div class="header-wrapper">
      <div class="banner">
        <img src="~/assets/imgs/flower-pot.png" />
      </div>
      <div class="avatar">
        <img src="~/assets/imgs/avatar.png" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
    }
  },
})
</script>

<style lang="scss" scoped>
.main-header {
  position: sticky;
  top: 0;
  height: 70px;
  color: #fff;
  background-color: #2f495e;
  .header-wrapper {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    .banner {
      padding: 0 20px;
      line-height: 70px;
      cursor: pointer;
      img {
        height: 64px;
      }
    }
    .avatar {
      padding: 0 20px;
      line-height: 70px;
      cursor: pointer;
      img {
        border-radius: 50%;
        width: 48px;
        height: 48px;
      }
    }
  }
}
</style>