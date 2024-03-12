<template>
  <ChildGreeting :full-name="fullName" />
</template>

<script>
import ChildGreeting from "./components/ChildGreeting.vue";

export default {
  components: {
    ChildGreeting,
  },
  data() {
    return {
      fName: "Jane",
      IName: "david",
    };
  },
  computed: {
    fullName() {
      return this.fName + " " + this.IName;
    },
  },
};
</script>
