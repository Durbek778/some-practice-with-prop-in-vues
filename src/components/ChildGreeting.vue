<template>
  <p>Hello, {{ fullName }}!</p>
</template>

<script>
export default { props: { fullName: { type: String, default: "Unknown" } } };
</script>
