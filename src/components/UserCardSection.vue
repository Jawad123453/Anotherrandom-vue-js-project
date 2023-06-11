<template>
    <div class="card">
      <div class="img-holder">
        <AnimationPlacerHolder width="150px" height="150px" borderRadius="50%"/>
      </div>
      <div class="card-text">
        <AnimationPlacerHolder height="36px" width="200px"/>
        <div class="summury">
          <AnimationPlacerHolder height="12px" width="400px"/>
          <AnimationPlacerHolder height="12px" width="400px"/>
          <AnimationPlacerHolder height="12px" width="400px"/>
        </div>
      </div>
    </div>
</template>

<script setup>
import AnimationPlacerHolder from './AnimationPlacerHolder.vue';
</script>

<style scoped>
.summury{
  display: flex;
  flex-direction: column;
  gap:12px;
  width:100%;
}
</style>