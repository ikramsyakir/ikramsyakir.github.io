<template>
  <div
    class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full md:w-1/3 md:min-w-[320px] lg:min-w-fit lg:w-full md:grow lg:grow-0"
  >
    <div
      class="h-32 bg-cover bg-center"
      :style="{ 'background-image': 'url(' + background + ')' }"
    ></div>
    <div class="w-full px-4 pt-2 flex -mt-12 items-end justify-between">
      <div class="avatar mb-5">
        <div
          class="w-24 rounded ring ring-primary ring-offset-base-100 ring-offset-2 -mt-3"
        >
          <img :src="picture" :alt="name" />
        </div>
      </div>
      <div class="flex flex-wrap-reverse justify-start items-center space-x-2">
        <a class="flex" :href="'mailto: ' + contact.email">
          <font-awesome-icon icon="fa-solid fa-envelope" size="lg" />
        </a>
        <a class="flex" :href="contact.twitter" target="_blank">
          <font-awesome-icon icon="fa-brands fa-twitter" size="lg" />
        </a>
        <a class="flex" :href="contact.facebook" target="_blank">
          <font-awesome-icon icon="fa-brands fa-facebook" size="lg" />
        </a>
        <a class="flex" :href="contact.github" target="_blank">
          <font-awesome-icon icon="fa-brands fa-github" size="lg" />
        </a>
        <a class="flex" :href="contact.linkedin" target="_blank">
          <font-awesome-icon icon="fa-brands fa-linkedin" size="lg" />
        </a>
      </div>
    </div>
    <div class="p-4 flex flex-wrap justify-between">
      <div class="mb-2 mr-2">
        <div class="text-lg font-bold">{{ name }}</div>
        <div class="text-sm text-gray-500">{{ position }}</div>
      </div>
    </div>
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Profile",
  components: {
    FontAwesomeIcon,
  },
  data() {
    return {
      name: "Ikram Syakir",
      position: "Software Engineer",
      picture: "src/assets/img/picture.png",
      contact: {
        email: "ikramsyakir@gmail.com",
        twitter: "https://twitter.com/IkramSyakir",
        facebook: "https://www.facebook.com/ikramxsyakir",
        github: "https://github.com/ikramsyakir",
        linkedin: "https://www.linkedin.com/in/ikramsyakir",
      },
      background: "src/assets/img/background.jpg",
    };
  },
};
</script>
