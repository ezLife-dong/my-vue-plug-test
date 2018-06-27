<style lang="less" scoped>
    @import url('styles/common.less');
</style>
<template>
    <div class="msg-wrapper">
        <span>hello!</span>
        <span class="account">{{data.name}}</span>
        <span></span>
    </div>
</template>
<script>
export default {
    name:'Msg',
    data () {
        return {}
    },
    props:{
        data:{
            type:Object
        }
    },
    methods:{

    },
    created(){
        let that = this;
    }
}
</script>


