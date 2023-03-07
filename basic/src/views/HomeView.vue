<template>
  <div class="home">
    <ModelItem v-model="changeItem"></ModelItem>
  </div>
</template>

<script>
import ModelItem from "@/components/ModelItem.vue";

export default {
  name: "HomeView",
  components: {
    ModelItem,
  },
  data() {
    return {
      changeItem: false,
    };
  },
};
</script>
