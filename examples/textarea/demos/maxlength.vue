<template>
  <div>
    <t-textarea
      v-model="value"
      placeholder="请输入描述文案，文本长度最多20，maxlength=20"
      :maxlength="20"
    ></t-textarea>
    <t-textarea
      v-model="value2"
      placeholder="请输入描述文案，最多20字符（一个汉字占两个字符长度），maxcharacter=20"
      :maxcharacter="20"
    ></t-textarea>
  </div>
</template>
<script>
export default {
  data() {
    return {
      value: '',
      value2: '',
    };
  },
  methods: {

  },
};
</script>
<style></style>
