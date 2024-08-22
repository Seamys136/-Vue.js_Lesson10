<template>
    <div>
        <UniqueHouse />
    </div>
</template>

<script>
import UniqueHouse from '@/components/homepage/UniqueHouse.vue';


export default {
  name: 'HomePage',
  components: {
    UniqueHouse,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .banner {
        width: 930px;
        height: 550px;
        margin-top: 20px;
        padding: 20px 120px 0px 180px;
    }

    .banner-image {
        width: 1180px;
        height: 758px;
    }

    
  
</style>
