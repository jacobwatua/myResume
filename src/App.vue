<template>
  <div class="app">
    <CvHeader />
    <CvSummary />
    <Skills />
    <Experience />
    <Education />
  </div>
</template>

<script>
import Education from "./components/education.vue";
import Experience from "./components/experience.vue";
import CvHeader from "./components/header.vue";
import Skills from "./components/skills.vue";
import CvSummary from "./components/summary.vue";
export default {
  components : {
    CvHeader,
    CvSummary,
    Skills,
    Experience,
    Education
}
}
</script>

<style>

</style>