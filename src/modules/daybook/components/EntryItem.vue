<template>
  <div class="entry-container mb-3 pointer p-2" @click="$router.push({name:'entry',params:{id:10}})">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">11</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2022, Lunes</span>
        </div>

      <div class="entry-description">
        Irure esse pariatur in pariatur fugiat qui laboris et deserunt deserunt nisi cupidatat elit. Adipisicing nostrud mollit dolore excepteur officia sunt laboris ullamco. Minim sint amet consequat et aliquip commodo aliqua incididunt exercitation. Minim ullamco commodo non proident laboris anim sunt aute ad fugiat sint dolor. Culpa consectetur anim exercitation ipsum nulla aliquip nulla incididunt dolor.
      </div>

  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

.entry-container {
  border-bottom:1px solid #2c3e50;
  transition: 0.2s all ease-in;


&:hover{
  background-color: lighten($color: gray, $amount: 45);
  transition: 0.2s all ease-in;
}

.entry-description{
  font-size: 12px;
}


}

</style>