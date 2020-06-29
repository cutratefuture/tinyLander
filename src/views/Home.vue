<template>
  <div class="home">
    <Lander msg="buildin'" />
  </div>
</template>

<script>
// @ is an alias to /src
import Lander from "@/components/Lander.vue";

export default {
  name: "Home",
  components: {
    Lander
  }
};
</script>
