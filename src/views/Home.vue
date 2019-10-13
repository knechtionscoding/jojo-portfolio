<template>
  <div>
    <CustomHeader />
    <Gallery />
    <custom-footer currentyear="2019" company="Jojo's Photography"/>
  </div>
</template>

<script>
import Gallery from '@/components/Gallery.vue';
import CustomHeader from '@/components/CustomHeader.vue'
import CustomFooter from '@/components/CustomFooter.vue'

export default {
  name: 'home',
  components: {
    Gallery,
    CustomHeader,
    CustomFooter
  },
};
</script>
