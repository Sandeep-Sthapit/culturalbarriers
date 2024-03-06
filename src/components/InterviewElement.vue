<template>
  <div class="interview">
    <p class="title is-4 red-color">Interview Questionairres</p>
    <p class="subtitle is-6">
      We conducted semi-structured interview using the following questions.
    </p>
    <table class="table is-narrow is-hoverable is-fullwidth is-striped">
      <thead>
        <tr>
          <th><abbr title="Question Number"><strong>QNo</strong></abbr></th>
          <th><strong>Question</strong></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th>1</th>
          <td>
            Tell us about a time when you had a struggle in programming due to culture and context?
          </td>
        </tr>
        <tr>
          <th>2</th>
          <td>
            When was this?
          </td>
        </tr>
        <tr>
          <th>&ensp;2a</th>
          <td>
            Follow up question: How long have you been in the United States?
          </td>
        </tr>
        <tr>
          <th>3</th>
          <td>
            How did it (issues with the programming problems or the culture) make you feel?
          </td>
        </tr>
        <tr>
          <th>&ensp;3a</th>
          <td>
            Follow up question: Did it impact the programming problem?
          </td>
        </tr>
        <tr>
          <th>4</th>
          <td>
            What made the question/scenario/experience difficult?
          </td>
        </tr>
        <tr>
          <th>5</th>
          <td>
            How comfortable were you with English at the time?
          </td>
        </tr>
        <tr>
          <th>6</th>
          <td>
            How comfortable were you with the culture at the time?
          </td>
        </tr>
        <tr>
          <th>7</th>
          <td>
            Did you overcome it?
          </td>
        </tr>
        <tr>
          <th>8</th>
          <td>
            What would you have your instructor do differently when a programming problem has cultural 
            background/embedded information that you are unaware of?
          </td>
        </tr>
        <tr>
          <th>9</th>
          <td>
            What would you have changed about the experience/scenario so that it 
            would have been easier to understand?
          </td>
        </tr>
        <tr>
          <th>10</th>
          <td>
            What speaking language(s) are you most comfortable in (and in what context)?
          </td>
        </tr>
        <tr>
          <th>11</th>
          <td>
            How comfortable are you with English?
          </td>
        </tr>
        <tr>
          <th>12</th>
          <td>
            How familiar are you with American culture?
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'InterviewElement'
}
</script>
<style scoped>
.interview {
  margin-top: 20px;
}
.divider {
  margin-top: 6px;
  width: 70%;
  height: 3px;
  border: none;
  background-color: #ce2029;
}
</style>
