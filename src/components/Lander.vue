<template>
  <b-container>
    <b-row>
      <b-col>
        <div class="hero">
          <img src="../assets/img/cry-cf.png" alt />
        </div>
      </b-col>
    </b-row>
    <b-row>
      <b-col md="12">
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
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  name: "Lander",
  props: {
    msg: String
  }
};
</script>

<style lang="css" scoped>
.hero img {
  height: 12em;
  background-color: #e8e9eb;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
li {
}
img {
  height: 20px;
  margin-right: 5px;
}
</style>
