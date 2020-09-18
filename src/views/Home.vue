<template>
  <b-container>
    <b-row>
      <b-col md="6">
        <Lander />
      </b-col>
      <!-- <b-col md="6">
        <Menu />
      </b-col> -->
    </b-row>
  </b-container>
</template>

<style lang="scss"></style>

<script>
import Lander from "../components/Lander.vue";
// import Menu from "../components/Menu.vue";

export default {
  components: {
    Lander,
    // Menu
  }
};
</script>
