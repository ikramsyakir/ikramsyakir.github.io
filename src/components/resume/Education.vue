<template>
  <div class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full p-4">
    <div class="text-lg font-bold mb-4">Education</div>
    <div class="flex flex-col divide-y">
      <div
        class="flex space-x-3 py-4"
        v-for="(item, index) in items"
        :key="index"
      >
        <div class="avatar rounded-lg overflow-hidden w-16 h-14">
          <img :src="item.logo" :alt="item.name" />
        </div>
        <div class="w-full">
          <span class="font-semibold">{{ item.education }}</span>
          <div class="text-sm text-gray-500 mt-3">
            <div>
              <font-awesome-icon
                icon="fa-solid fa-graduation-cap"
                class="mr-1"
              />
              <span>{{ item.location }}</span>
            </div>
            <div class="mt-1">
              <font-awesome-icon icon="fa-solid fa-calendar" class="mr-2" />
              <span>{{ item.duration }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Education",
  components: {
    FontAwesomeIcon,
  },
  data() {
    return {
      items: [
        {
          logo: "src/assets/img/logo/uitm.png",
          name: "UiTM Melaka",
          education:
            "Bachelor of Information Technology (Hons.) Information System Engineering",
          location: "UiTM Melaka, Campus Jasin",
          duration: "2017 - 2020",
        },
        {
          logo: "src/assets/img/logo/politeknik.png",
          name: "Polytechnic Sultan Mizan Zainal Abidin",
          education: "Diploma in Information Technology (Programming)",
          location:
            "Polytechnic Sultan Mizan Zainal Abidin, Dungun, Terengganu",
          duration: "2013 - 2016",
        },
      ],
    };
  },
};
</script>
