<template>
  <div id="greeting">
    <p v-if="name">Helo {{ name }}!</p>
    <p v-else>Hi am Doggo, who are yu?</p>
  </div>
</template>

<script>
export default {
  name: "Hello",
  props: {
    name: String,
  },
};
</script>
