<script lang="ts" setup>
import L from "leaflet";
import { onMounted } from "vue";

onMounted(() => {
  L.map("map").setView([51.505, -0.09], 13);
});
</script>

<template>
  <div id="map">map</div>
</template>

<style lang="scss" scoped>
#map {
  height: 180px;
}
</style>
