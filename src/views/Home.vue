<template>
  <div class="home">
    <HelloWorld msg="CT Davies Films" />
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {
    HelloWorld: () =>
      import(/* webpackChunkName: "HelloWorld" */ "@/components/HelloWorld.vue")
  }
};
</script>
