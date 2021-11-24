<template>
  <div class="home">
    <home-background
    >
        <template #header="{ header }">
            <div>
                dsafdaaf
                {{ header.name }}
            </div>
        </template>
    </home-background>
  </div>
</template>
<script>
import HomeBackground from "../components/HomeBackground.vue";
export default {
  components: { HomeBackground },
  name: "Home",
  data() {
    return {};
  },
  methods: {
    
  }
};
</script>
<style scoped>
</style>
