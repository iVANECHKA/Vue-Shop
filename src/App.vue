<script setup>
import Header from './components/Header-block.vue'
import CardList from './components/Card-list.vue'
</script>

<template>
  <div class="bg-white w-4/5 mx-auto rounded-xl shadow-xl mt-14">
    <Header />

    <main>
      <div class="p-10">
        <h1 class="text-3xl font-bold mb-8">Все кроссовки</h1>
        <CardList />
      </div>
    </main>
  </div>
</template>
