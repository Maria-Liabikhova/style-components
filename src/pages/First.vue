<template>
  <div>
    <card><router-link to="/second" class="card__link">Another page</router-link> </card>
    <btn />
  </div>
</template>

<script>
import card  from '../components/Card.vue'
import btn  from '../components/Btn.vue'
export default {
  components:  {card, btn} 
}
</script>