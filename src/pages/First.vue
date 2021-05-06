<template>
  <div>
    <card><router-link to="/second" class="card__link">Another page</router-link> </card>
    <Btn />
  </div>
</template>

<script>
import card  from '../components/Card.vue'
import Btn  from '../components/Btn.vue'
export default {
  components:  {card, Btn} 
}
</script>