<template>
  <div>
    <h1>
      {{ msg }}
    </h1>
  </div>
</template>

<script>
export default {
  name: "Title",
  props: {
    msg: String,
  },
};
</script>
