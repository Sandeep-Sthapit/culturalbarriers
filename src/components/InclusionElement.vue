<template>
  <div class="inclusion">
    <p class="title is-4 red-color">Eligibility Criteria</p>
    <p class="subtitle is-6">
      Participants who met all the criteria were eligible to participate in the research.
    </p>
    <div class="content">
      <ol type="1">
        <li>18 years or older</li>
        <li>Having prior programming experience</li>
        <li>Born and completing high school outside the United States</li>
        <li>Struggled due to cultural context</li>
        <li>Consent to participate</li>
      </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: 'InclusionElement'
}
</script>
<style scoped>
.inclusion{
  margin-top: 12px;
}
.divider {
  margin-top: 6px;
  width: 70%;
  height: 3px;
  border: none;
  background-color: #ce2029;
}
</style>
