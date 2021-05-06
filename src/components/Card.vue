<template>
  <div class="card">
    <div class="card__flexwrap">
      <h1 :class="cssModificator.title" class="card__title">Hello World!</h1>
      <img :src="require('@/assets/img/colourfill.jpg')" alt="colourfull friends" :class="cssModificator.img" class="card__img">
    </div>
    <p :class="cssModificator.text" class="card__text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Earum quo ipsam quae, dolore corrupti aut sunt ducimus quod repellat sint blanditiis maxime suscipit. Qui libero, inventore dolores odit mollitia fuga.</p>
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    cssModificator: {
      type: Object,
      required: false,
      default: () => ({
        title: '',
        text: '',
        img: ''
      })
    }
  },
  data() {
    return {

    }
  }
}
</script>