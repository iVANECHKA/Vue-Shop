<script setup>
defineProps({
  title: String,
  price: Number
})
</script>

<template>
  <div class="product">
    <h2>
      Товар: <span>{{ title }}</span>
    </h2>
    <h3>
      Цена: <span>{{ price }}</span>
    </h3>
  </div>
</template>

<style>
.product {
  outline: 2px dotted black;
  width: 200px;
}
</style>
