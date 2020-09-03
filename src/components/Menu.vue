<template>
  <div>
    <ul>
      <li>
        <b-link to="/">home</b-link>
      </li>
      <li>
        <b-link to="/music">Music</b-link>
      </li>
      <li>
        <b-link to="/art">Art</b-link>
      </li>
      <li>
        <b-link to="/blog">Blog</b-link>
      </li>
      <li>
        <b-link to="/contact">Contact</b-link>
      </li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
ul {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  list-style-type: none;

  li {
    padding: 6px 0;

    a {
      position: relative;
      display: block;
      padding: 4px 0;
      font-family: Lato, sans-serif;
      color: #ecf0f1;
      text-decoration: none !important;
      text-transform: uppercase;
      transition: 0.5s;

      &::after {
        position: absolute;
        content: "";
        top: 100%;
        left: 0;
        width: 100%;
        height: 3px;
        background: #df2935;
        transform: scaleX(0);
        transform-origin: right;
        transition: transform 0.3s;
      }

      &:hover {
        color: #95a5a6;
      }

      &:hover::after {
        transform: scaleX(1);
        transform-origin: left;
      }
    }
  }
}
</style>
