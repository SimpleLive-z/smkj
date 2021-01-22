<template>
  <div>
    <div class="header">
      <HeaderTop/>
    </div>
    <div class="aside">
      <Aside/>
    </div>
    <slot name="banner"></slot>
    <div class="main">
      <slot name="slot1"></slot>
      <slot name="slot2"></slot>
      <slot name="slot3"></slot>
      <slot name="slot4"></slot>
      <slot name="slot5"></slot>
    </div>
    <div class="footer">
      <FooterBottom/>
    </div>
  </div>
</template>

<script>
import HeaderTop from "./HeaderTop";
import FooterBottom from "./FooterBottom";
import Aside from "./Aside";

export default {
  name: "Public",
  components: {
    HeaderTop,
    FooterBottom,
    Aside
  }
}
</script>

<style scoped>
div {
  padding: 0;
  margin: 0;
}
</style>
