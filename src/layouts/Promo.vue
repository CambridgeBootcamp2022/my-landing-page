<template>
  <div class="flex flex-wrap">
    <div
      class="w-full md:w-6 px-4 py-8 md:px-6 lg:px-8"
      style="
        background: linear-gradient(
            0deg,
            rgba(0, 0, 0, 0.42),
            rgba(0, 0, 0, 0.42)
          ),
          linear-gradient(246.36deg, #007261 15.22%, #005347 65.22%);
      "
    >
      <div class="text-4xl text-white mb-3 font-medium">
        Promo Title Placeholder
      </div>
      <p class="line-height-3 mt-0 mb-7 p-0 text-white text-2xl">
        Malesuada bibendum arcu vitae elementum curabitur vitae nunc. Aliquam
        nulla facilisi cras fermentum. Et egestas quis ipsum suspendisse
        ultrices.
      </p>
      <Button label="READ STORY" class="p-button-secondary text-2xl"></Button>
    </div>
    <div
      class="w-full md:w-6 bg-no-repeat bg-cover"
      style="
        background: url('images/blocks/ecommerce/promosection/promo-section-2-1.jpg');
        min-height: 400px;
      "
    ></div>
  </div>
</template>

<script>
import Button from 'primevue/button'

export default {
  name: 'Promo',
  components: {
    Button,
  },
}
</script>

<style scoped></style>
