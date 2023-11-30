<script setup>
import { RouterLink, RouterView,  } from 'vue-router'
import { ref, onMounted } from 'vue'
import { query, collection, getDocs, onSnapshot} from 'firebase/firestore'
import db from './firebase/init.js'



</script>

<template>
  <div>
    <RouterView />
  </div>
</template>

<style scoped>

</style>
