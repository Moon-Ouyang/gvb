<template>
    <div class="gvb_admin">
        <aside>
            <div>
                <i class="iconfont icon-yonghu"></i>
            </div>
        </aside>
        <div class="main">
            <header></header>
            <div class="tabs"></div>
            <main></main>
        </div>
    </div>
</template>

<script>
</script>

<style lang="scss">
.gvb_admin {
   width: 100%;
   
   aside {
        width: 240px;
        height: 100vh;
        background-color: #2b3539;    
   }

   .main{
        width: calc(100% - 240px);
        header {
            height: 60px;
            background-color: white;
        }

        .tabs{
            height: 30px;
            border: 1px solid #f0eeee;
        }
        main{
            background-color: #f0eeee;
            height: calc(100vh - 90px);
        }
   }
}

</style>