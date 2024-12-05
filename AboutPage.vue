<template>
  <div class="about">
    <h1>How I Built This Page</h1>
    <p>
      I installed Vue.js using Vue CLI, initialized a new project, and customized the components.
      For hosting, I used GitHub Pages. Difficulties included setting up routing and deployment,
      which I resolved by carefully following Vue Router and GitHub Pages documentation.
    </p>
  </div>
</template>

<script>
export default {
  name: "AboutPage",
};
</script>

<style>
.about {
  font-family: Arial, sans-serif;
  padding: 20px;
  background-color: #f5f5f5;
  border-radius: 8px;
}
</style>
