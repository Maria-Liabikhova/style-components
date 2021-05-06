<template>
  <div>
    <button class="btn" :class="{'btn--green': isGreen}">I am a button!</button>
  </div>
</template>

<script>
export default {
  props: ['isGreen'],
}
</script>