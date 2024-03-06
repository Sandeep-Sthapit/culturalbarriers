<script setup>
import TitleElement from './components/TitleElement.vue'
import FooterElement from './components/FooterElement.vue'
import InclusionElement from './components/InclusionElement.vue'
import InterviewElement from './components/InterviewElement.vue'
import FormElement from './components/FormElement.vue'
</script>

<template>
  <div class="app-div">
    <TitleElement />
    <div class="content">
      <InclusionElement/>
      <InterviewElement/>
    </div>
    <FormElement />
    <FooterElement />
  </div>
</template>

<style scoped>
.app-div{
  position: relative;
  width: 100%;
}
</style>
