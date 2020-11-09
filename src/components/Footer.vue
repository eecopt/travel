<template>
    <div class="footer">
        <div>
            <div class="row">更多旅行线路开发中</div>
            <div class="row-a">热爱出发 | Passion leads us here</div>   
        </div>
        <div>
            <div class="row-b">技术支持:<a href="#">量化网络</a></div>
        </div>     
    </div>
</template>
<style scoped>
    .row{
        border-top: 1px solid #333;
        width: 180px;
        margin-bottom: 20px;
        margin: 0 auto;
        padding-top: 20px;
        text-align: center;
        font-size: 18px
    }
    .row-a{
        text-align: center;
        margin-top: 20px;
        font-size: 15px;
        color: rgb(155, 145, 145);
        margin-bottom: 30px;
    }
    .row-b{
        border-top: 10px solid lightGreen;
        text-align: center;
        padding-top: 30px;
        color: lightgray
    }
    a{
        text-decoration: none;
        color: rgb(160, 144, 144);

    }
</style>
<script>
export default {
    name:'app-footer',
    data(){
        return {

        }
    }
}
</script>
