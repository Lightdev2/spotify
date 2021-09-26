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
  created() {
    let vh = window.innerHeight * 0.01;
    document.documentElement.style.setProperty("--vh", `${vh}px`);
    window.addEventListener("resize", () => {
      let vh = window.innerHeight * 0.01;
      document.documentElement.style.setProperty("--vh", `${vh}px`);
    });
  },
};
</script>

<style lang="scss">
.home {
  display: flex;
  height: calc(var(--vh, 1vh) * 100);
  flex-direction: column;
  &__content {
    display: flex;
    flex: 1;
  }
}
</style>
