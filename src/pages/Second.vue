<template>
  <div>
    <card class="card--violet" :cssModificator="{title: 'card__title--green', text: 'card__text--orange', btn: 'btn--green'}">
      <router-link to="/" class="card__link">Another page</router-link> 
    </card>
    <btn class="btn--green"></btn>
  </div>
</template>

<script>
import card from "../components/Card.vue";
import btn from "../components/Btn.vue";
export default {
  components: { card, btn },
  data() {
    return {
      isGreen: true,
    };
  },
};
</script>