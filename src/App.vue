<script setup>
import Card from './components/Card.vue';
import UserCardSection from './components/UserCardSection.vue';
</script>

<template>
  <main>
    <Suspense>
      <Card />
      <template #fallback>
        <UserCardSection />
      </template>
    </Suspense>
  </main>
</template>

<style>
*{
  padding:0;
  box-sizing: border-box;
  margin:0;
  font-family: sans-serif;
}
</style>
