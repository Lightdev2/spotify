<template>
  <div class="home">
    <div class="home__content">
      <LeftBar></LeftBar>
      <Navigator></Navigator>
    </div>
    <HomeFooter></HomeFooter>
  </div>
</template>

<script>
import HomeFooter from "@/components/HomeFooter";
import LeftBar from "@/components/LeftBar";
import Navigator from "@/components/Navigator";

export default {
  name: "Home",
  components: {
    HomeFooter,
    LeftBar,
    Navigator,
  },
};
</script>

<style lang="scss">
.home {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  &__content {
    display: flex;
    flex: 1;
  }
}
</style>
