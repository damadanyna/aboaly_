<template>
  <HelloWorld/>
</template>

<script setup>

import { useRouter } from 'vue-router'
import {
    ref,
} from 'vue'


const router = useRouter()
  //
  onMounted(() => {
    router.replace('/auth/signin')
  })
</script>
