<template>
  <div class="learn">
    <select v-model="selectedLesson">
      <option v-for="(lessonItem, index) in lessonList" v-bind:key="index" :value="lessonItem[0]">{{lessonItem[1]}}</option>
    </select>
    <component v-bind:is="selectedLesson"></component>
  </div>
</template>

<script>
  import Lesson1 from './Lessons/Lesson1.vue';
  import Lesson2 from './Lessons/Lesson2.vue';
  import Lesson3 from './Lessons/Lesson3.vue';
  import Lesson4 from './Lessons/Lesson4.vue';

  export default {
    name: 'Lesson',
    components: {
      Lesson1,
      Lesson2,
      Lesson3,
      Lesson4
    },
    data() {
      return {
        lessonList: [
          ['Lesson1', 'Lesson 1'],
          ['Lesson2', 'Lesson 2'],
          ['Lesson3', 'Lesson 3'],
          ['Lesson4', 'Lesson 4'],
        ],
        selectedLesson: 'Lesson1'
      }
    },
    computed: {
      componenteAtual() {
        return this.SelectedLesson
      }
    }
  }
</script>