<template>
    
    <!-- start admin-card  -->
    <div class="admin-card">
        <slot></slot>
    </div>
    <!-- end admin-card  -->

</template>

<script>
export default {
     name: 'AdminCard',
}
</script>

<style lang="scss" scoped>
   .admin-card{
       background: #FFFFFF;
       border-radius: 10px;
       padding: 22px;
       margin-bottom: 20px;
       .admin-card-header{
           display: flex;
           .admin-card-header-search{
               flex: 3;
           }
           .admin-card-header-operate{
               width: 100%;
               flex: 1;
               text-align: right;
           }
       }
   }
</style>