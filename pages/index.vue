<template>
  <div class="root">
  <All/>
  <Ender/>
  </div>
</template>

<script>
import All from "../components/All.vue";
import Ender from "../components/Ender.vue";
export default {
    name: "IndexPage",
    components: { All,Ender }
}
</script>
