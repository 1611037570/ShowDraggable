<template>
  <SnowDraggable />
  <div style="width: 100%; height: 400px; border: 1px solid red">
    <SnowDraggable parent :firstPosition="null" />
    <SnowDraggable parent />
  </div>
</template>

<script setup lang="ts">
import SnowDraggable from './components/snowDraggable'
</script>

<style>
body,
* {
  margin: 0 !important;
  padding: 0 !important;
}
</style>
