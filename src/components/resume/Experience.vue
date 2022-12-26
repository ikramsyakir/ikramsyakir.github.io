<template>
  <div class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full p-4">
    <div class="text-lg font-bold mb-4">Experience</div>
    <div class="flex flex-col divide-y">
      <div
        class="flex space-x-3 py-4"
        v-for="(item, index) in items"
        :key="index"
      >
        <div
          class="avatar rounded-lg overflow-hidden w-16 h-14"
          v-if="item.company_logo"
        >
          <img :src="item.company_logo" :alt="item.company_name" />
        </div>
        <div
          class="avatar placeholder rounded-lg overflow-hidden w-16 h-14"
          v-else
        >
          <div class="bg-neutral-focus text-neutral-content">
            <span class="text-xl tracking-widest">
              {{ item.company_initial_name }}
            </span>
          </div>
        </div>
        <div class="w-full">
          <span class="font-semibold">{{ item.position }}</span>
          <div class="text-sm text-gray-500 mt-1">
            <div>
              <font-awesome-icon icon="fa-solid fa-briefcase" class="mr-2" />
              <span>{{ item.location }}</span>
            </div>
            <div class="mt-1">
              <font-awesome-icon icon="fa-solid fa-calendar" class="mr-2" />
              <span>{{ item.duration }}</span>
            </div>
          </div>
          <div class="p-4 text-justify text-sm -mb-4">
            <ul class="list-disc">
              <li v-for="(desc, index) in item.description" :key="index">
                {{ desc }}
              </li>
            </ul>
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
  name: "Experience",
  components: {
    FontAwesomeIcon,
  },
  data() {
    return {
      items: [
        {
          company_logo: "src/assets/img/logo/aidan.png",
          company_name: "Aidan Technologies Sdn Bhd",
          company_initial_name: "AT",
          position: "Software Engineer",
          location: "Aidan Technologies Sdn Bhd, Setapak, Wilayah Persekutuan",
          duration: "Feb 2020 - Present",
          description: [
            "Participate in team and client meeting.",
            "Assist on portal and system development.",
            "Maintaining current and previous project.",
          ],
        },
        {
          company_logo: "",
          company_name: "Atas Awan Sdn Bhd",
          company_initial_name: "AA",
          position: "Web Developer",
          location: "Atas Awan Sdn Bhd, Ampang, Selangor",
          duration: "August 2016 - Feb 2017",
          description: [
            "Maintained mobile top-up shop management system and implements new features to enhance user experience.",
            "Developed a web integration that is connected to the POS system which can perform transactions through mobile application.",
          ],
        },
        {
          company_logo: "src/assets/img/logo/dbp.jpeg",
          company_name: "Dewan Bahasa dan Pustaka",
          company_initial_name: "DB",
          position: "Intern",
          location: "Dewan Bahasa dan Pustaka, Kuala Lumpur",
          duration: "Dec 2014 - April 2015",
          description: [
            "Developed a website with WordPress together with designing the interface using CSS.",
          ],
        },
      ],
    };
  },
};
</script>
