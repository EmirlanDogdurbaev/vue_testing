<template lang="eng">
  <div>
    <HelloWorld msg="hello my world " :ax="['list1','list2','list3']" />
    <ByWorld />
  </div>
</template>
<script>
import HelloWorld from "./HelloWorld.vue";
import ByWorld from "./ByWorld.vue";

export default {
  name: "PagesContainer",
  components: { HelloWorld, ByWorld },
};
</script>
<style></style>
