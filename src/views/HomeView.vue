<template>
  <div class="container">
     <b> Upload your TRSX file to parse! </b>
       <TRSXFileUpload />
  </div>

</template>

<script>
// @ is an alias to /src
 import TRSXFileUpload from '@/components/TRSXFileUpload.vue'

export default {

  components: { 
    TRSXFileUpload
  }
}
</script>

