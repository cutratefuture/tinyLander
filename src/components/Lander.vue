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
        <ul class="red text-center social">
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
            <a href="https://www.deviantart.com/cutratefuture" target="_blank">
              <img src="../assets/icons/da.png" alt="deviant art icon" />
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
  height: 13.3em;
  background-color: #e8e9eb;
  padding: 1.1em;
}

ul {
  list-style-type: none;
  margin: 0;
  height: 1em;
  width: 13em;
  padding: 0;
}

.social {
  padding-left: 18px;
}

ul li {
  display: inline !important;
}

li > a > img {
  margin-top: 1em;
  margin-right: 20px;
  height: 23px;
}

img {
  height: 20px;
  margin-right: 5px;
}
</style>
