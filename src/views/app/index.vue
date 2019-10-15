<template>
  <div>
    <!-- <keep-alive> -->
    <component is="compact-sidebar"></component>
    <!-- </keep-alive> -->
  </div>
</template>

<script>
import { mapGetters, mapActions } from "vuex";

export default {
  components: {},
  data() {
    return {};
  },
  computed: {
    ...mapGetters(["getThemeMode"])
  },
  methods: {}
};
</script>
