<script>
import datePicker from "@alireza-ab/vue3-persian-datepicker/nuxt";

export default {
  data() {
    return {
      date: null,
    };
  },
  components: {
    datePicker,
  },
};
</script>

<template>
  <div>
    <datePicker v-model="date" />
  </div>
</template>
