<template>
    <header>
        <div class="flex between">
            <h1 class="header-logo">estra inc.</h1> 
            <nav class="header-nav">
                <ul>
                    <li><a v-on:click="clickHome()">home</a></li>
                    <li><a v-on:click="clickAbout()">about</a></li>
                    <li><a v-on:click="clickService()">service</a></li>
                    <li><a v-on:click="clickWorks()">works</a></li>
                    <li><a v-on:click="clickWorks()">price</a></li>
                    <li><a v-on:click="clickContact()">contact</a></li>
                </ul> 
            </nav>
        </div>
    </header>
</template>
<script>
export default{
    methods:{
        clickHome(){
            alert('homeページへいきます')
            this.$router.path('/')
        },
        clickAbout(){
            alert('aboutページへいきます')
            this.$router.path('/About')
        },
        clickService(){
            alert('serviceへいきます')
        },
        clickWorks(){
            alert('worksへいきます')
        },
        clickContact(){
            alert('contactへいきます')
        }
    }
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
        cursor: pointer;
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