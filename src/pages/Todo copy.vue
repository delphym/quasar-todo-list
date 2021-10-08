<template>
  <q-page class="bg-grey-3 column">
    <q-list class="bg-white">
      <q-item v-ripple>
        <q-item-section avatar>
          <q-checkbox
            v-model="color"
            color="primary" />
        </q-item-section>
        <q-item-section>
          <q-item-label>Teal</q-item-label>
        </q-item-section>
      </q-item>
    </q-list>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue';

export default
  defineComponent({
  })

  data(){
    return {
      tasks: [
        {
          title: 'Get bananas',
          done: false
        },
        {
          title: 'Eat bananas',
          done: false
        },
        {
          title: 'Poo bananas',
          done: false
        }
      ]}
  }
</script>
