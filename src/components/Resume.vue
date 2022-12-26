<template>
  <div
    class="h-screen p-2 md:p-5 md:pb-2 overflow-scroll flex flex-col justify-between"
  >
    <div
      class="max-w-4xl mx-auto flex flex-col lg:flex-row space-y-4 lg:space-y-0 lg:space-x-4 min-w-[250px] mb-5"
    >
      <div
        class="flex flex-col space-y-4 lg:min-w-[280px] md:flex-row md:space-y-0 md:space-x-4 lg:flex-col lg:space-y-4 lg:space-x-0"
      >
        <Profile />
        <Skills />
      </div>
      <div class="flex flex-col space-y-4">
        <About />
        <Experience />
        <Education />
        <Achievement />
        <Project />
      </div>
    </div>
  </div>
</template>

<script>
import Profile from "@/components/resume/Profile.vue";
import Skills from "@/components/resume/Skills.vue";
import About from "@/components/resume/About.vue";
import Experience from "@/components/resume/Experience.vue";
import Education from "@/components/resume/Education.vue";
import Achievement from "@/components/resume/Achievement.vue";
import Project from "@/components/resume/Project.vue";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Resume",
  components: {
    Project,
    Achievement,
    Education,
    Experience,
    About,
    Skills,
    Profile,
  },
};
</script>
