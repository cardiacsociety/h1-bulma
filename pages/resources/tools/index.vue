<template>
</template>
<script>
  export default {
    beforeCreate() {
      this.$router.push(this.$route.path + "/calculators")
    }
  }
</script>
