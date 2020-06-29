<template>
  <div class="wrapper">
    <div class="content">
      <div class="notes">
        <img class="art" src="../assets/img/cry-cf.png" alt />
        <h1>{{ msg }}</h1>
        <p>stay tuned.</p>
        <small>
          peace out.
          <br />6/29/20
        </small>
      </div>

      <ul class="socialList">
        <li>
          <a href="https://github.com/cutratefuture" target="_blank">
            <img src="../assets/icons/gh.png" alt="github icon" />
          </a>
        </li>
        <li>
          <a href="https://instagram.com/cutratefuture" target="_blank">
            <img src="../assets/icons/in.png" alt="instagram icon" />
          </a>
        </li>
        <li>
          <a href="https://soundcloud.com/cutratefuture" target="_blank">
            <img src="../assets/icons/sc.png" alt="soundcloud icon" />
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Lander",
  props: {
    msg: String
  }
};
</script>

<style lang="scss" scoped>
// .container {
//   width: 40rem;
//   margin: auto;
// }
</style>
