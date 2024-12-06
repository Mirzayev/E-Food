<template>
  <div class="text-black">
    Hirepleropvme
  </div>
</template>



<script>
import {createRouter, createWebHistory} from "vue-router";
import {ref} from  'vue'

// const router = createRouter(createWebHistory())

const count = ref(4)


const a = 10

function increment(){
  const returnResult =  count.value + a
  return returnResult

}
const result = increment()

console.log(result)
</script>


