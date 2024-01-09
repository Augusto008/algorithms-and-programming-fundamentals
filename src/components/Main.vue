<template>
  <div class="hello col-8 mx-auto">
    <h1>Welcome to Algorithms and Programming Fundamentals</h1>
    <br />
    <h2>Intro</h2>
    <p>
      This project objective is to initiate you in algorithms and programming fundamentals and give you trust to create your first programms.
    </p>
  
    <h2>Dinamics</h2>
    <p>
      Your experience is divided in two parts: <strong>theoretical</strong> and <strong>practical</strong>.<br />
      For better use, you can chose, in the navigation menu, between the options <strong>lessons</strong> or <strong>practice</strong>.<br />
      <strong>Lessons</strong> contain explanations and quizzes about the content.<br />
      <strong>Practice</strong> contain the quizzes, only. For those who want to test themeselves.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
