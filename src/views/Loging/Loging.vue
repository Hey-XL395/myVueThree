<template>
  <div class="loging-page">
    <div class="loging">This is an loging page</div>
  </div>
</template>
<script lang="ts">
// import { defineComponent } from '@vue/composition-api'
import { defineComponent, ref, reactive } from "vue";

export default defineComponent({
  setup(props, { attrs, slots, emit }) {
    console.log(props);
    console.log(attrs);
    console.log(slots);
    console.log(emit);
    return {};
  },
});
</script>
<style lang="scss">
.loging-page {
    width: 100%;
    height: 100vh;
    overflow-x: hidden;
    background:repeating-linear-gradient(30deg, #79b, #79b 15%, #58a 0, #58a 30%);
  .loging {
    width: 60%;
    margin: 0 auto;
    margin-top: 10%;
    height: 500px;
    background: #fff;
    border: 1px red solid;
    border-radius: 5px;
  }
}
</style>

