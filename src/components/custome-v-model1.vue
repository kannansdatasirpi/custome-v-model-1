<template>
  <input type="text" /> <!--2.add the input element in tem-->
</template>

<script>
export default {
  name: 'Input-val',    // 1.name , component as input
  }
</script>

<!--3.add the our own style-->
<style scoped>        
input[type="text"]{      
  display: block;           
  width: 400px;
  padding: 6px 12px;
  font-size: 14px;
  line-height: 1.4;
  color: #555;
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 4px;
}
</style>
