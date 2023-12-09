<template>
  <v-container fluid>
    <div class="d-flex flex-wrap justify-space-around">
      <VWordAmount v-for="word in groupedWords"
                   :key="word.name"
                   :name="word.name"
                   :amount="word.amount"
      />
    </div>
  </v-container>
</template>

<script>
import VWordAmount from "@/components/VWordAmount.vue";
export default {
  components : {VWordAmount},
  data: function () {
    return {
      groupedWords: [
        {
          name: 'word',
          amount: 30
        },
        {
          name: 'pronoum',
          amount: 45
        },
        {
          name: 'elements',
          amount: 10
        },
        {
          name: 'names',
          amount: 100
        }
      ]
    }
  }
}
</script>

<style>
</style>