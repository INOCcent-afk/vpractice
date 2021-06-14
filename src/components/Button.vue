<template>
  <button @click="click()" :style="{ background: color }" class="btn">
    {{ text }}
  </button>
</template>

<script>
export default {
  name: "Button",
  props: {
    text: String,
    color: String,
  },
  methods: {
    click() {
      console.log("click");
    },
  },
};
</script>
