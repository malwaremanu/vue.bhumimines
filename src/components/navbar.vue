<template>
  <div class="p-6 bg-green-200 text-green-800 font-semibold">
    <Button @click="test" title="Login">asd title</Button>
  </div>
</template>

<script>
import Button from "../components/buttons.vue";
export default {
  name: "navbar",
  components: { Button },
  methods: {
    test() {
      alert("sample alert");
    }
  }
};
</script>