<template>
    <div id="login">这里是登录页<el-button>默认按钮</el-button></div>
    
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>//scoped使css只在该文件中有效，不会污染其他文件的css
#login {
    height: 100vh;//vh基于窗口大小自适应，50vh始终占窗口大小的一半，随窗口大小的变动而一起变动
    background-color: #344a5f;
}
</style>
