<template>
    <div class="page">
        <div class="page__hd">
            <h1 class="page__title">Button</h1>
            <p class="page__desc">按钮</p>
        </div>
        <div class="page__bd page__bd_spacing">
            <button class="weui-btn weui-btn_primary">页面主操作 Normal</button>
            <button class="weui-btn weui-btn_primary weui-btn_loading"><i class="weui-loading"></i>页面主操作 Loading</button>
            <button class="weui-btn weui-btn_disabled weui-btn_primary">页面主操作 Disabled</button>
            <button class="weui-btn weui-btn_default">页面次要操作 Normal</button>
            <button class="weui-btn weui-btn_default weui-btn_loading"><i class="weui-loading"></i>页面次操作 Loading</button>
            <button class="weui-btn weui-btn_disabled weui-btn_default">页面次要操作 Disabled</button>
            <button class="weui-btn weui-btn_warn">警告类操作 Normal</button>
            <button class="weui-btn weui-btn_warn weui-btn_loading"><i class="weui-loading"></i>警告类操作 Loading</button>
            <button class="weui-btn weui-btn_disabled weui-btn_warn">警告类操作 Disabled</button>
            
            <div class="button-sp-area">
                <button class="weui-btn weui-btn_plain-default">按钮</button>
                <button class="weui-btn weui-btn_plain-default weui-btn_plain-disabled">按钮</button>
                <button class="weui-btn weui-btn_plain-primary">按钮</button>
                <button class="weui-btn weui-btn_plain-primary weui-btn_plain-disabled">按钮</button>
                <button class="weui-btn weui-btn_mini weui-btn_primary">按钮</button>
                <button class="weui-btn weui-btn_mini weui-btn_default">按钮</button>
                <button class="weui-btn weui-btn_mini weui-btn_warn">按钮</button>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="less" scoped>
@import url("../base.less");
.button-sp-area {
    margin: 0 auto;
    padding: 15px 0;
    width: 60%;
}
</style>

