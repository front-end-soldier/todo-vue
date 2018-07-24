<template>
    <div class="footer fixed">
        <ul>
            <!--  使用<router-link>标签来实现页面的跳转 -->
            <li><router-link to='/'>首页</router-link></li>
            <li><router-link to='manage'>todo</router-link></li>
        </ul>
    </div>
</template>

在style中设置 scoped 的作用是声明作用域，样式只在该页面生效，不会污染全局
<style scoped>
	li a{display: inline-block; width: 100%; height:100%;}
	.footer{width:100%; height:50px; bottom:0;}
	ul{display: flex; height:100%; line-height:50px;}
	ul li{flex: 1; background-color:#f1f1f1;}
	.isIndex li:first-child{background-color:#d3d3d3;}
	.isIndex li:first-child a{color:#41b883;}
	.isManage li:last-child{background-color:#d3d3d3;}
	.isManage li:last-child a{color:#41b883;}
</style>