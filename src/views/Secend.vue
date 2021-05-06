<template>
  <div >
    <div class="card">
      <div class="flex ">
        <h1 >Hello world!!</h1>
        <div class="flex flex--fix"></div>
      </div>

    </div>
  </div>
</template>

<script>
</script>

<style scoped>
.card{
  height: 300px;
  width: 500px;
}
.flex{
  display: flex;
}
.flex--fix{
  height: 100px;
  width: 300px;
  background-image: url(../assets/img/candy.jpg);
  background-size: cover;
}
.bor{
  border: 1px dashed red
}
</style>
