<template>
  <div class="button-container">
    <button>{{ title }}</button>
  </div>
</template>

<style>
.button-container button {
  background: black;
  padding: 30px;
  color: #cecece;
  cursor: pointer;
  will-change: background color;
  transition: background cubic-bezier(0.4, 0, 0.14, 1) 300ms, color cubic-bezier(0.4, 0, 0.14, 1) 300ms;
}

.button-container button:hover {
  background: #cecece;
  color: black;
}

</style>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    }
  }
}
</script>
