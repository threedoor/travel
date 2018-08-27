<template>
<div class='header'>
    <div class='header-left'>返回</div>
    <div class='header-input'>输入城市景点</div>
    <div class='header-right'>城市</div>
</div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang='stylus' scoped>
.header {
    display: flex;
    line-height: 0.86 rem;
    background: #00bcd4;
    color: #fff;

    .header-left {
        width: 0.64 rem;
        float: left;
    }

    .header-input {
        flex: 1;
        height: 0.64 rem;
        line-height: 0.64 rem;
        margin-top: 0.12 rem;
        margin-left: 0.2 rem;
        background: #fff;
        border-radius: 0.1 rem;
    }

    .header-right {
        width: 1.24 rem;
        float: right;
        text-align: center;
    }
}
</style>
