<template>
  <button>{{ title }}</button>
</template>

<script>
export default {
  props: ["title"],
};
</script>
<style sccoped>
button {
  color: white;
  background-color: #59bbd8;
  padding: 0.5rem;
  border: none;
  border-radius: 5px;
}
</style>