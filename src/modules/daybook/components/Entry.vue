<template>
  <div
    class="entry-container mb-3 pointer p-2"
    @click="$router.push({ name: 'entry', params: { id: 10 } })"
  >
    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold"> 15 </span>
      <span class="mx-1 fs-5">Julio </span>
      <span class="mx-2 fs-light">2023, Viernes</span>
    </div>
    <div class="entry-description">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita,
      consequatur quia! Tempora sed dolorem minus atque magnam laborum vitae,
      consequatur non laboriosam, aliquid voluptas accusantium vero et iusto ut
      dignissimos.
    </div>
  </div>
</template>


<style lang="scss" scoped>
.entry-container {
  border-bottom: 1px solid #2c3e50;
  transition: 0.2s all ease-in;

  &:hover {
    background-color: lighten($color: grey, $amount: 45);
    transition: 0.2s all ease-in;
  }

  .entry-description {
    font-size: 12px;
  }
}
</style>