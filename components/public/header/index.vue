<template>
    <el-row :gutter="15" class="m-header">
        <el-col :span="6">
            <geo></geo>
        </el-col>
        <el-col :span="6">
            <user></user>
        </el-col>
        <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
    </el-row>
</template>

<script>
import Geo from './geo'
import User from './user'
export default {
    components:{
        Geo,
        User
    }
}
</script>

<style lang="sass" scoped>
@import "@/assets/css/public/layout.scss";
</style>
