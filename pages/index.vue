<template lang="pug">
div.container
  z-header/
  z-footer/
</template>


<script>
import z_header from '~/components/header.vue';
import z_footer from '~/components/footer.vue';

export default {
  components: {
    'z-header': z_header,
    'z-footer': z_footer
  }
};
</script>
