<template>
  <div>

  </div>
</template>

<script>
import {getInfo} from '@/api/user'
export default {
  mounted(){
    getInfo();
  }
}
</script>
