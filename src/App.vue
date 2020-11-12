<template>
  <div id="app">
    <h1>App.vue</h1>
    <GmapMap
      :center="{ lat: 10, lng: 10 }"
      :zoom="7"
      map-type-id="terrain"
      style="width: 500px; height: 300px"
    >
    </GmapMap>
  </div>
</template>

<style>
#app {
  text-align: center;
}
</style>
