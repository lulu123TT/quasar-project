<template>
  <div class="q-pa-md q-gutter-md fixed-center">
    <q-card class="my-card q-pa column justify-center" style="min-width: 300px;min-height: 300px;">
      <q-card-section>
        <div class="text-h5">Register</div>
      </q-card-section>
      <q-card-section>
        <q-input v-model="text" label="Username"/>
        <q-input v-model="text" label="Password"/>
      </q-card-section>
      <q-card-section class="row justify-center">
        <q-btn color="primary" label="GO" />
      </q-card-section>
    </q-card>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const  text = ref('')
</script>

<style scoped lang="sass">
.my-card
  max-width: 340px
</style>
