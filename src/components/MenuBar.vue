<template>
  <nav class="navbar w-full bg-transparent">
    <div class="flex-1"></div>
    <div>
      <ThemeDropdown />
    </div>
  </nav>
</template>

<script>
import ThemeDropdown from "./menu/ThemeDropdown.vue";

export default {
  name: "MenuBar",
  components: {
    ThemeDropdown,
  },
};
</script>
