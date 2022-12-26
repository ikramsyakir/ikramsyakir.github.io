<template>
  <div class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full p-4">
    <div class="text-lg font-bold mb-4">Project</div>
    <div class="flex flex-col divide-y">
      <div
        class="flex space-x-3 py-4"
        v-for="(item, index) in items"
        :key="index"
      >
        <div class="w-full">
          <span class="font-semibold">
            <a :href="item.link" class="link link-hover" target="_blank">
              {{ item.name }}
            </a>
          </span>
          <div class="text-justify text-sm mt-4">
            <p>{{ item.description }}</p>
            <ul class="p-6 list-disc -mt-5 -mb-4">
              <li v-for="(list, index) in item.lists" :key="index">
                {{ list }}
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Project",
  data() {
    return {
      items: [
        {
          name: "STPC",
          link: "https://github.com/ikramsyakir/stpc",
          description:
            "STPC is stand for Sepak Takraw Point Counter. It assists keeping track of the points.",
          lists: [
            "Fill in the opposing team's name.",
            "Choose which team starts the service or make it random.",
            "Record the time during the game.",
            "Show which team is serving for each point.",
            "Summary after the match ends (time period, winner etc.)",
          ],
        },
        {
          name: "Magnetize",
          link: "https://github.com/ikramsyakir/magnetize",
          description:
            "Magnetize is a web application built with modern technologies such as Laravel, Bootstrap 4, RESTful API etc.",
          lists: [
            "The purpose I built this software because I want to keep this software up to date with current modern technology using the framework that I developed.",
            "Aside from that, I use this software as an API to learn other frameworks (Mobile Apps, SPA, Desktop Apps etc.)",
          ],
        },
      ],
    };
  },
};
</script>
