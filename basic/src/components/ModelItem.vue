<template>
  <div class="about">
    <input
      type="input"
      v-bind:checked="checked"
      @change="$emit('change', $event.target.checked)"
    />
  </div>
</template>
<script>
export default {
  name: "ModelItem",
  props: {
    checkd: Boolean,
  },
};
</script>
