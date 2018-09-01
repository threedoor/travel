<template>
<div class='header'>
    <div class='header-left'>
        <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class='header-input'>
        <span class="iconfont">&#xe632;</span>
        输入城市景点</div>
    <div class='header-right'>
        城市 <span class="iconfont">&#xe6aa;</span>
        </div>
</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang='stylus' scoped>
 @import "~style/varibles.styl"
.header {
    display: flex;
    line-height: 0.86 rem;
    background: $bgColor;
    color: #fff;

    .header-left {
        .back-icon{
            text-align: center;
            font-size: 0.4 rem;
        }
        width: 0.64 rem;
        float: left;
    }

    .header-input {
        flex: 1;
        height: 0.64 rem;
        line-height: 0.64 rem;
        margin-top: 0.12 rem;
        margin-left: 0.2 rem;
        padding-left: 0.2 rem;
        background: #fff;
        border-radius: 0.1 rem;
        color:#ccc;
    }

    .header-right {
        width: 1.24 rem;
        float: right;
        text-align: center;
    }
}
</style>
