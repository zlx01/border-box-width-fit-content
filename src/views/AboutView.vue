<template>
  <div class="about">
    <h1 @click="test">This is an about page</h1>
  </div>
</template>

<script>
import { Toast } from "vant";

export default {
  name: "AboutView",
  methods: {
    test() {
      Toast({
        message: "验证码错误",
        duration: 0,
      });
    },
  },
};
</script>
