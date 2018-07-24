<template>
    <div>        
        <img src="../../assets/todo.png" alt="">

        <p>欢迎使用todolist</p>
        <footer-nav></footer-nav>
        <!-- 3使用组件 -->
    </div>
</template>

<script>

// 1引入组件
import FooterNav from '../../components/footer'  
export default {
    // 2局部注册
    components:{
        FooterNav
    }
}
</script>

<style>
    img{
        width: 300px;
        height: 300px;
    }
    p{
        font-size: 25px;
    }
</style>