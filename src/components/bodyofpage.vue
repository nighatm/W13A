<template>
  <div class="page-body">
    <div></div>
    <h3>Body container text</h3>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus iusto, repudiandae quaerat dolorum nulla iure hic commodi saepe laudantium enim cupiditate veritatis velit at pariatur sapiente consequatur perspiciatis et iste.</p>
    <div></div>
    <h3>Body container Image</h3>
    <div></div>
    <h3>Body container links</h3>
    <div></div>
    <div>
      <side-panel />
    </div>
  </div>
</template>

<script>
import SidePanel from "../components/sidepanel.vue";

export default {
  name: "page-body",
  components: {
    name: PagePanel,
  },
};
</script>

<style scoped>
.page-body {
  display: grid;
  justify-items: center;
  align-items: center;
  width: 80%;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr;
  margin: 2em;
  background-color: rgb(89, 189, 132);
}
</style>