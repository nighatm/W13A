<template>

  <div class="page-body">
    <div>
    <side-panel />
    </div>
    <div></div>
    <h3>Body container text</h3>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus iusto, repudiandae quaerat dolorum nulla iure hic commodi saepe laudantium enim cupiditate veritatis velit at pariatur sapiente consequatur perspiciatis et iste.</p>
    <div></div>
    <h3>Body container Image</h3>
    <div></div>
    <h3>Body container links</h3>
    <div></div>
    
  </div>
</template>

<script>
import SidePanel from "../components/sidepanel.vue";

export default {
  name: "page-body",
  components: {
    SidePanel
  }
};
</script>

<style scoped>
.page-body {
  display: grid;
 
  align-self: right;
  width: 100%;
  grid-template-columns: 4fr 6fr;

  background-color: rgb(89, 189, 132);
}
</style>