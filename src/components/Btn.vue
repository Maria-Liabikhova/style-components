<template>
  <button class="btn" :class="{'btn--green': isGreen}">I am a button!</button>
</template>

<script>
export default {
  props: ['isGreen'],
}
</script>