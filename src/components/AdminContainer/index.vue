<template>
    
    <!-- start admin-container -->
    <div class="admin-container">
        <slot></slot>
    </div>
    <!-- end admin-container-->

</template>

<script>
export default {
     name: 'AdminContainer',
}
</script>

<style lang="scss" scoped>
   .admin-container{
       padding: 20px 20px;
       background: #F0F2F5;
       min-height: calc(100vh - 84px);
       max-height: auto;
   }
</style>