<template>
  <div class="reports-container">
    <div class="reports-text">reports</div>
  </div>
</template>

<script>
import { mapGetters } from "vuex";

export default {
  name: "reports",
  computed: {
    ...mapGetters(["name"])
  }
};
</script>

<style lang="scss" scoped>
.reports {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
