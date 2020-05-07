<template>
    <header>
        <div class="flex between">
            <h1 class="header-logo">estra inc.</h1> 
            <nav class="header-nav">
                <ul>
                    <li><a href="#">home</a></li>
                    <li><a href="#">about</a></li>
                    <li><a href="#">service</a></li>
                    <li><a href="#">works</a></li>
                    <li><a href="#">price</a></li>
                    <li><a href="#">contact</a></li>
                </ul> 
            </nav>
        </div>
    </header>
</template>
<script>
export default {

}
</script>
<style scoped>
    header{
        height: 70px;
        background: #000;
    }
    .header-logo{
        font-size: 20px;
        font-weight: bold;
        margin-left: 35px;
        color: #fff;
        line-height: 70px;
    }
    .header-nav li{
        display: inline-block;
        margin-right: 35px;
        font-size: 16px;
    }
    .header-nav a{
        color: #fff;
    }

    @media screen and (max-width: 768px){
        .header-nav{
            display: none;
        }
        #hamberger{
            width: 40px;
            height: 40px;
            position: absolute;
            cursor: pointer;
            z-index: 100;
            top: 15px;
            right: 20px;
            transition: .4s;
        }
        #hamberger span{
            position: absolute;
            left: 2px;
            display: block;
            width: 35px;
            height: 2px;
            background: #fff;
            transition: .8s;
        }
        #hamberger span:nth-of-type(1){
            top: 10px;
        }
        #hamberger span:nth-of-type(2){
            top: 20px;
        }
        #hamberger span:nth-of-type(3){
            top: 30px;
        }
    }
</style>