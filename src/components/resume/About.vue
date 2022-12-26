<template>
  <div class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full p-4">
    <div class="text-lg font-bold mb-4">About me</div>
    <div class="flex flex-col space-y-4 text-justify">
      <p>{{ text }}</p>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "About",
  data() {
    return {
      text: "Specialized in back end development. Comfortable and experienced in various back end stack development. I am the man when it comes to back end development which serve the purpose as the one who is responsible developing the logic as well as the engine of the end product.",
    };
  },
};
</script>
