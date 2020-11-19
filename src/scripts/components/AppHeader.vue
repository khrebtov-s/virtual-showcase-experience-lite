<template>
  <header>
    <div class="logo">
      <div class="title">
        Virtual<br />
        Showcase
      </div>
    </div>
    <div class="actions"></div>
  </header>
</template>

<script>
import AppButton from './AppButton.vue';

export default {
    components: { AppButton },
    data: () => ({ }),
};
</script>

<style lang="scss" scoped>
header {
    display: flex;
    height: 60px;
    padding: 0 72px;
    align-items: center;
    justify-content: space-between;
}

.logo {
    display: flex;
    align-items: center;

    img {
        width: 98px;
        height: 28.14px;
    }

    .title {
        margin: 0 10px;
        padding: 0 10px;
        font-size: 12px;
        font-weight: bold;
        line-height: 16px;
        text-transform: uppercase;
        color: #78787A;
        border-left: 1px solid #78787A;
    }
}
</style>