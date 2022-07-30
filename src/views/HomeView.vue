<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <counter />
    <counterSquared />
    <buttons />
    <colorCode />
  </div>
</template>

<script>
export default {
  name: "HomeView",
  components: {
    counter: require("@/components/CounterComp.vue").default,
    counterSquared: require("@/components/CounterSquared.vue").default,
    buttons: require("@/components/ButtonsComp.vue").default,
    colorCode: require("@/components/ColorCode.vue").default,
  },
};
</script>

<style scoped>
div {
  margin-bottom: 10px;
}
.counter {
  font-size: 80px;
}
</style>
