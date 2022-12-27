<template>
  <div
    class="flex flex-col grow space-y-4 sm:flex-row sm:space-y-0 sm:space-x-4 lg:space-x-0 lg:space-y-4 lg:flex-col"
  >
    <div class="rounded-xl bg-base-100 shadow-xl overflow-hidden w-full p-4">
      <div class="text-lg font-bold mb-2">Skills</div>
      <div class="flex flex-col divide-y">
        <div
          class="flex space-x-2 py-4"
          v-for="(category, index) in categories"
          :key="index"
        >
          <div class="w-full">
            <span class="font-semibold">{{ category.name }}</span>
            <div class="flex flex-wrap lg:flex-row mt-3">
              <div
                class="btn btn-xs normal-case cursor-default mb-2 mr-2"
                v-for="(item, index) in category.items"
                :key="index"
              >
                {{ item }}
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Skills",
  data() {
    return {
      categories: [
        {
          name: "Backend",
          items: [
            "PHP",
            "MySQL",
            "MariaDB",
            "RESTful API",
            "Redis",
            "Nginx",
            "Apache",
          ],
        },
        {
          name: "Frontend",
          items: ["HTML", "CSS", "JavaScript", "NPM", "AJAX", "Axios", "PWA"],
        },
        {
          name: "Framework",
          items: [
            "Laravel",
            "Vue.js",
            "Bootstrap",
            "TailwindCSS",
            "Yii2",
            "Flutter",
            "Ionic",
          ],
        },
        {
          name: "Version Control",
          items: ["GitHub", "GitLab"],
        },
      ],
    };
  },
};
</script>
