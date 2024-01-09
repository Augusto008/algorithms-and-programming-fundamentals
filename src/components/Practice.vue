<template>
  <div class="practicing">
    <select v-model="selectedPractice">
      <option v-for="(PracticeItem, index) in lessonList" v-bind:key="index" :value="PracticeItem[0]">{{PracticeItem[1]}}</option>
    </select>
    <component v-bind:is="selectedPractice"></component>
  </div>
</template>

<script>
  import Practice1 from './Practice/Practice1.vue';
  import Practice2 from './Practice/Practice2.vue';
  import Practice3 from './Practice/Practice3.vue';
  import Practice4 from './Practice/Practice4.vue';

  export default {
    name: 'Practice',
    components: {
      Practice1,
      Practice2,
      Practice3,
      Practice4
    },
    data() {
      return {
        lessonList: [
          ['Practice1', 'Practice 1'],
          ['Practice2', 'Practice 2'],
          ['Practice3', 'Practice 3'],
          ['Practice4', 'Practice 4'],
        ],
        selectedPractice: 'Practice1'
      }
    },
    computed: {
      componenteAtual() {
        return this.selectedPractice
      }
    }
  }
</script>