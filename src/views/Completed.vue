<template>
    <div id="Completed">
        <LeftMenu></LeftMenu>
    </div>
    <div id="Content">
        Completed
    </div>
</template>

<script>
import LeftMenu from './../components/Layout/LeftMenu'

export default {
    name: 'Completed',
    components:{
        LeftMenu
    },
    data () {
        return {
        }
    }
}
</script>

<style lang="scss" scoped>
#Completed{
    width:300px;
    height:100%;
    float:left;
}
</style>
