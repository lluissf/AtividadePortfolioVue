<script></script>
<template>
  <header>
    <nav>
      <ul>
        <li><router-link to="/"> Blog</router-link></li>
        <li><router-link to="/works"> Works</router-link></li>
        <li><router-link to="/"> Contact</router-link></li>
      </ul>
    </nav>
  </header>
</template>
<style scoped>
header ul li {
  text-align: center;
  padding: 10px 0 10px 0;
}
@media (min-width: 900px) {
  header ul {
    display: flex;
    justify-content: right;
  }

  header ul li {
    margin: 0px 20px 0px 20px;
  }
}
</style>