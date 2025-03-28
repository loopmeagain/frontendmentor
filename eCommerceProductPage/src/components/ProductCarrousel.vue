<template>
    <figure>
      <img class="main_image" src=".././assets/image-product-1.jpg" alt="Image portraying a photo of the product">
    </figure>
    <section>
      <img class="thumbnail" src=".././assets/image-product-2-thumbnail.jpg" alt="Image portraying a photo of the product">
      <img class="thumbnail" src=".././assets/image-product-3-thumbnail.jpg" alt="Image portraying a photo of the product">
      <img class="thumbnail" src=".././assets/image-product-4-thumbnail.jpg" alt="Image portraying a photo of the product">
    </section>
</template>
<style scoped>
.main_image {
  max-width: 28rem;
  border-radius: 1rem;
  margin: 1rem;
}
.thumbnail {

}
</style>
<script>
export default {
  name: 'ProductCarrousel'
}
</script>
