<template>
  <div>
    <CustomHeader />
    <Gallery />
  </div>
</template>

<script>
import Gallery from '@/components/Gallery.vue';
import CustomHeader from '@/components/CustomHeader.vue'

export default {
  name: 'home',
  components: {
    Gallery,
    CustomHeader
  },
};
</script>
