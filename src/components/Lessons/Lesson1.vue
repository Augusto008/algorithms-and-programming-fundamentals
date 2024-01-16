<template>
  <div class="col-10 col-lg-8 mx-auto">
    <article>
      <h1>Basic Concepts</h1>
      <p class="text-center">
        Before we can start I need to introduce you to some concepts.
      </p>
      <p>
        &nbsp;&nbsp;<strong>Algorithms:</strong> the way we organize and sequentialize our thoughts to solve a problem. Simplifying, <strong>Algorithms</strong> are sequences of instructions or commands to be followed to execute a job or solve a problem.
      </p>
      <p>
        &nbsp;&nbsp;<strong>Programming:</strong> In this context, <strong>Programming</strong> is the act of translate algorithms to a language that computer can understand, developing computer routines or programms.
      </p>
      <p>
        &nbsp;&nbsp;<strong>Computer:</strong> a tool to solve problems. A computer is composed of two parts:
      </p>
      <div class="px-0 px-sm-4">
        <table class="table table-secondary table-striped-columns table-bordered">
          <thead class="table-primary">
            <tr class="table-dark">
              <th colspan="2">Computer</th>
            </tr>
            <tr>
              <th>Hardware</th>
              <th>Software</th>
            </tr>
          </thead>
          <tbody class="table-group-divider">
            <tr>
              <td>Physical parts of the computer.</td>
              <td>Logic parts of the computer.<br/>Its systems, programs and routines.</td>
            </tr>
          </tbody>
        </table>
      </div>
      <br />
      <div>
        <h2 class="text-start border-bottom">Algorithms</h2>
        <p>
          &nbsp;&nbsp;The objective of algorithm and programming here is to solve problems using the computer, but it's not just about this.
        </p>
        <p>
          &nbsp;&nbsp;<b>Algorithms</b> can be found everywhere in our lives. In short, every action that you can imagine step by step is an algorithm.
        </p>
        <div class="px-0 px-sm-4">
          <h3 class="text-start border-bottom">Algorithms Types</h3>
          <p>
            &nbsp;&nbsp;There are some diferent types of algorythms as you'll see:
          </p>
          <table class="table table-secondary table-striped table-bordered">
            <thead class="table-primary">
              <tr>
                <th>Type</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody class="table-group-divider">
              <tr>
                <th>Narrative Description</th>
                <td>Narrative of the steps of a problem solution.</td>
              </tr>
              <tr>
                <th>Fluxogram</th>
                <td>Graphically represent the problem solution.</td>
              </tr>
              <tr>
                <th>Pseudocode</th>
                <td>Transformation to natural language code format.</td>
              </tr>
            </tbody>
          </table>
          <p>
            To make it easy understand. Here is a narrative description algorithm to make an algorythm. 
          </p>
          <div class="px-0 px-sm-4">
            <pre class="p-2 text-start text-wrap bg-dark text-warning">1- Understand the problem<br>2- Find a way to solve it<br>3- Put it on paper<br>4- Organize it into steps<br>5- Decide the algorithm format you want<br>6- Transcribe your steps in choosed format<br>&nbsp;&nbsp;6.1- If you want to use all formats, preferably use them in the following order<br>&nbsp;&nbsp;&nbsp;&nbsp;6.1.1- Narrative Description<br>&nbsp;&nbsp;&nbsp;&nbsp;6.1.2- Fluxogram<br>&nbsp;&nbsp;&nbsp;&nbsp;6.1.3- Pseudocode</pre>
          </div>
        </div>
        <br/>
      </div>
      <div>
        <h2 class="text-start border-bottom">Programming</h2>
        <p>
          &nbsp;&nbsp;The pseudocode contains the instructions that computer needs to follow to make what we want, but computer can't understand our nature language.
          <br />
          &nbsp;&nbsp;To communicate with the computer a special languagem called programming languages.
        </p>
        <div class="px-0 px-sm-4">
          <h3 class="text-start border-bottom">Programming Languages</h3>
          <p>
            There are many types of programming languages. For now, we'll focus on just a few:
          </p>
          <table class="table table-secondary table-striped table-bordered">
            <thead class="table-primary">
              <tr>
                <th>Type</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody class="table-group-divider">
              <tr>
                <th>Compiled</th>
                <td>Source code is converted in a program that can only be read by the Operational System for which it was developed.</td>
              </tr>
              <tr>
                <th>Interpreted</th>
                <td>Source code is interpreted in real time when run on the system.</td>
              </tr>
            </tbody>
          </table>
        </div>
        <div class="px-0 px-sm-4">
          <h3 class="text-start border-bottom">Programming Paradigms</h3>
          <p>
            &nbsp;&nbsp;Programming languages obey paradigms.
            <br />
            &nbsp;&nbsp;In sum, a paradigm is a pattern to be followed by the language. Another words, a paradigm of a language says the way in which it should be used.
          </p>
          <table class="table table-secondary table-striped table-bordered">
            <thead class="table-primary">
              <tr>
                <th>Paradigm</th>
                <th>Description</th>
              </tr>
            </thead>
            <tbody class="table-group-divider">
              <tr>
                <th>Procedural</th>
                <td>Based on procedures executed in sequence.</td>
              </tr>
              <tr>
                <th>Non-Procedural</th>
                <td>Based in what the program has to do, but not how.</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </article>
  </div>
</template>

<script>
  export default {
    name: 'Lesson1'
  }
</script>

<style scoped lang="scss">
  p {
    text-align: justify;
  }
</style>