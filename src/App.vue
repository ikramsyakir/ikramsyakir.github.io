<template>
  <MenuBar />
  <Resume />
  <FooterBar />
</template>

<script>
import MenuBar from "@/components/MenuBar.vue";
import Resume from "@/components/Resume.vue";
import FooterBar from "@/components/FooterBar.vue";
import { themeChange } from "theme-change";

export default {
  components: {
    MenuBar,
    Resume,
    FooterBar,
  },
  mounted() {
    themeChange(false);
  },
};
</script>
