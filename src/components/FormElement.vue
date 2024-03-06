<template>
  <section class="hero is-primary form-element">
    <div class="hero-body">
      <p class="subtitle">We would love to hear your suggestions</p>
      <a href="https://forms.gle/FDUNRu9nKzhLyb1b6" target="_blank"
        ><button
          class="button is-danger is-large is-outlined is-inverted is-responsive feedback-btn"
        >
          Feedbback Form
        </button></a
      >
    </div>
  </section>
</template>

<script>
export default {
  name: 'FormElement'
}
</script>
<style scoped>
.form-element {
  margin-top: 12px;
  background-color: #ce2029;
}
.feedback-btn {
  border-width: 2px;
}
</style>
