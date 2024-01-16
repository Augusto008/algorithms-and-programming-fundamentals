<template>
  <div class="learn pb-5 mb-5">
    <div class="row justify-content-center my-4 mx-0">
      <div class="col-auto">
        <select id="lesson" class="form-select " v-model="selectedLesson">
          <option v-for="(lessonItem, index) in lessonList" v-bind:key="index" :value="lessonItem[0]">
            {{lessonItem[1]}}
          </option>
        </select>
      </div>
    </div>
    <component v-bind:is="selectedLesson"></component>
    <div class="d-flex justify-content-end px-4">
      <button class="btn btn-light rounded-circle mt-5" @click="backToStart">
        <img src="..\assets\arrow-narrow-top-alignment-svgrepo-com.svg" alt="return to top" width="40px;">
      </button>
    </div>
  </div>
</template>

<script>
  import Lesson1 from "./Lessons/Lesson1.vue";
  import Lesson2 from "./Lessons/Lesson2.vue";
  import Lesson3 from "./Lessons/Lesson3.vue";
  import Lesson4 from "./Lessons/Lesson4.vue";

  export default {
    name: "Lesson",
    components: {
      Lesson1,
      Lesson2,
      Lesson3,
      Lesson4
    },
    data() {
      return {
        lessonList: [
          ["Lesson1", "Lesson 1"],
          ["Lesson2", "Lesson 2"],
          ["Lesson3", "Lesson 3"],
          ["Lesson4", "Lesson 4"],
        ],
        selectedLesson: "Lesson1"
      }
    },
    computed: {
      actualComponent() {
        return this.SelectedLesson
      }
    },
    methods: {
      backToStart() {
        document.body.scrollTop = 0; // For Safari
        document.documentElement.scrollTop = 0; // For Chrome, Firefox, IE and Opera
      }
    }
  }
</script>