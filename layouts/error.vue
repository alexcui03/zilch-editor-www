<template lang="pug">
div.container
  h1(v-if='error.statusCode === 404') 页面不存在
  h1(v-else) 未知错误
</template>

<script>
import z_header from '~/components/header.vue';
import z_footer from '~/components/footer.vue';

export default {
  props: ['error']
};
</script>
