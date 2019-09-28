<template>
  <div>Hello {{message}} from {{sender}}</div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      message: "Ram",
      sender: "Shyam"
    };
  }
};
</script>