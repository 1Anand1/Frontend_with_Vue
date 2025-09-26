<script>
export default {
  data() {
    return { name: " Anand Dandavate", status: false };
  },
};
</script>

<template>
  <h1>{{ name }}</h1>
  <p v-if="status">User is active</p>
  <p v-else>User is inactive</p>
</template>
