<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="main-text">
    <h1 class="c-primary">{{ msg }}</h1>
    <h3>Kjellarn er en sammling av artister og musikere fra Trondheim, som leverer grove materialer rett fra kjellarn.
    </h3>
  </div>
</template>
