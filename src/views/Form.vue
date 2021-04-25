<template>
  <div class="form">
    <Form />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import Form from "@/components/Form.vue";

@Component({
  components: {
    Form,
  },
})
export default class AboutView extends Vue {}
</script>
