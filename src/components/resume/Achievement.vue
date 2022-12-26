<template>
  <div class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full p-4">
    <div class="text-lg font-bold mb-4">Achievement</div>
    <div class="flex flex-col divide-y">
      <div
        class="flex space-x-3 py-4"
        v-for="(item, index) in items"
        :key="index"
      >
        <div class="w-full">
          <span class="font-semibold">{{ item.title }}</span>
          <div class="text-sm text-gray-500 mt-1">
            <div>
              <font-awesome-icon icon="fa-solid fa-location-dot" class="mr-1" />
              <span>{{ item.location }}</span>
            </div>
          </div>
          <div class="text-justify text-sm mt-5">
            <p>{{ item.description }}</p>
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
  name: "Achievement",
  components: {
    FontAwesomeIcon,
  },
  data() {
    return {
      items: [
        {
          title: "MyHackathon 2020 Winner",
          location: "Cradle Fund Sdn Bnd",
          description:
            "Develop web-based applications that provide solutions for end-to-end asset maintenance activities. With implementation using web, app, online and offline, and Subject-matter expert (SME) verified reporting, maintenance work is faster and more efficient.",
        },
        {
          title: "Grand Prize Winner National Big App Challenge 4.0",
          location:
            "ASEAN Data Analytics eXchange (ADAX), Bangsar South, Kuala Lumpur",
          description:
            "Attend as one of the Ukay Wizards teammates and demonstrating prototype of mobile application known as MH Guardian.",
        },
        {
          title: "Grand Prize Winner Malaysia Airlines Hackathon 2017",
          location: "Malaysia Airlines Academy, Petaling Jaya, Selangor",
          description:
            "Developed a web-based application for unaccompanied minors to let ground staff fill in the check-in form which then will generate an email that will be send to parents to track their minor with mobile application.",
        },
      ],
    };
  },
};
</script>
