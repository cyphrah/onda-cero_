<template>
  <div class="app">
    <div class="header">
      <Header />
    </div>
    <div class="body">
      <div class="components_holder">
        <div class="banner">
          <Banner />
          <img src="">
        </div>
        <div class="cards_holder">
          <div class="card_holder">
            <CardSquare />
            <CardSquare />
            <CardSquare />
          </div>
          <div class="card_holder">
            <CardM/>
            <CardSquare/>
          </div>
          <div class="card_holder">
            <CardSquareLarge/>
          </div>
        </div>
      </div>
    <div class="menu_holder">
      <MenuHolder/>
    </div>
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import CardSquare from '../components/CardSquare.vue'
import CardM from '../components/CardM.vue'
import CardSquareLarge from '../components/CardSquareLarge.vue'
import MenuHolder from '../components/MenuHolder.vue'
import Header from '../components/Header.vue'
export default {
  data() {
    return {};
  },
  components: { Banner, CardSquare, CardM, CardSquareLarge, MenuHolder, Header }
}
</script>

<style lang="postcss" scoped>
.app {
  @apply w-full bg-slate-300 min-h-[100vh] overflow-x-hidden justify-center p-4
}

.card_holder {
  @apply flex items-center w-[1000px] overflow-auto;
}
.body{
  @apply pb-10 pt-4
}
.menu_holder{
  @apply fixed bottom-0 left-0 w-full;
}
.banner{
}
.header{
  @apply flex w-full;
}
</style>