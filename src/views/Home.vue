<template>
    <div class="home">
        <div id="firstview">
            <p class="catchcopy fadein">機械ではできない仕事を</p>
            <div class="news flex fadein">
                <div class="news-content">
                    <p class="news_date">2019/01/01</p>
                    <p class="news_title">ニュースタイトルがここには入ります。3月の決算報告書</p>
                </div>
                <div class="news-icon">news</div>
            </div>
        </div>

        <div id="hamburger">
            <span></span>
            <span></span>
            <span></span>
        </div>

        <main>
            <div class="mission fadein">
                <div class="mission-content">
                    <h2 class="mission_title">お客様のために進化する成長企業であり続ける</h2>
                    <p class="mission_text">
                        顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。
                    </p>
                    <a href="" class="common-btn mission-btn">ミッション詳細</a>
                </div>
                <div class="mission-img fadein">
                    <img src="../assets/img/mission-img.jpg" alt="">
                </div>
            </div>

            <div class="service fadein">
                <h2 class="service-title section-title">service</h2>
                <div class="service-content fadein">
                    <div class="service-img">
                        <img src="../assets/img/service2.jpg" alt="">
                    </div>
                    <div class="service-content_inner">
                        <h3 class="mgb-15">web制作事業</h3>
                        <p class="mgb-15">コーチングのミッション</p>
                        <p class="mgb-15">
                            ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
                        </p>
                        <a href="" class="common-btn service-btn">サービス詳細</a>
                    </div>
                </div>
                <div class="service-content fadein">
                    <div class="service-img service-img_second">
                        <img src="../assets/img/service1.jpg" alt="">
                    </div>
                    <div class="service-content_inner service-content_inner-second">
                        <h3 class="mgb-15">web制作事業</h3>
                        <p class="mgb-15">コーチングのミッション</p>
                        <p class="mgb-15">
                            ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります
                        </p>
                        <a href="" class="common-btn service-btn">サービス詳細</a>
                    </div>
                </div>
            </div>

            <div class="company fadein">
                <div class="recruit-company flex">
                    <div class="recruit-company_size company-img">
                        <h2 class="company-title section-title">company<br><span>会社概要</span></h2>
                    </div>
                    <div class="recruit-company_size recruit-img">
                        <h2 class="company-title section-title">recruit<br><span>採用情報</span></h2>
                    </div>
                </div>
            </div>

            <div class="faq fadein">
                <h2 class="faq-title">FAQ</h2>
                <p class="faq-title-jp">良くある質問</p>
            </div>

            <div class="contact fadein">
                <h2 class="contact-title section-title">contact<br><span>お問い合わせ</span></h2>
                <p class="contact-subtitle section-title">お気軽にお問い合わせください。</p>
                <p class="contact-text">資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力フォームにご記入お願いいたします。</p>
                <a href="" class="common-btn contact-btn">お問い合わせへ</a>
            </div>
        </main>
    </div>
</template>
<script>

</script>
<style scoped>
/*------------------------*/
/*         header         */
/*------------------------*/
#firstview{
    height: 100vh;
    background: url(../assets/img/eyecatch.jpg) no-repeat;
    background-size: cover;
    background-position:  center;
    position: relative;
}

.catchcopy{
    position: absolute;
    top: 60%;
    left: 10%;
    font-size: 60px;
    font-style: italic;
    font-weight: bold;
    color: #fff;
    line-height: 1;
}

/*------------------------*/
/*         news           */
/*------------------------*/
.news{
    position: absolute;
    bottom: 0;
    right: 0;
    width: 50%;
}
.news-content{
    background: #fff;
    width: 80%;
    height: 70px;

}

.news_date{
    padding-left: 5px;
}

.news_title{
    padding: 0 15px;
}
.news-icon{
    display: inline-block;

    background: #000;
    width: 20%;
    height: 70px;
    line-height: 70px;
    text-align: center;
    color: #fff;
}

/*------------------------*/
/*         mission        */
/*------------------------*/

.mission{
    position: relative;
    background: #000;
    margin-bottom: 10%;
    z-index: 999;
}

.mission-content{
    padding: 10% 0 10% 20%;
    box-sizing: border-box;
    width: 70%;
}

.mission_title,.mission_text{
    margin-bottom: 30px;
    color: #fff;
}

.mission_title{
    font-size: 30px;
}



.mission-img{
    width: 40%;
    position: absolute;
    bottom: -10%;
    right: 5%;
    z-index: -999;

}



/*------------------------*/
/*         service        */
/*------------------------*/
.service{
    background: #E5E5E5;
    margin-bottom: 10%;
}
.service-title{
    text-align: center;
    padding: 20px 0;
}

.service-content{
    position: relative;
    padding-bottom: 15%;
}
.service-img{
    width: 50%;
    margin-left: 50%;
}

.service-img_second{
    margin: 0 50% 0 0;
}

.service-content_inner{
    position: absolute;
    top: 15%;
    left: 20%;
    background: #fff;
    width: 40%;
    padding: 5% 5%;
    box-sizing: border-box;
}

.service-content_inner-second{
    left: 40%;
}



.service-btn{
    border: 1px solid #000;
    margin: 0 0 0 auto;
}


/*------------------------*/
/*        recruit         */
/*------------------------*/
.company{
    margin-bottom: 10%;
}

.recruit-company_size{
    width: 48%;
    height: 300px;
    position: relative;
}

.company-img{
    background: url(../assets/img/company.jpeg)center/cover no-repeat;
}

.recruit-img{
    background: url(../assets/img/recruit.jpg)center/cover no-repeat;
}

.company-title{
    text-align: center;
    color: #fff;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    -webkit-transform: translate(-50%,-50%);
    -moz-transform: translate(-50%,-50%);
    -ms-transform: translate(-50%,-50%);
    -o-transform: translate(-50%,-50%);
}

.company-title span{
    color: #fff;
}

/*------------------------*/
/*        faq             */
/*------------------------*/
.faq{
    width: 70%;
    background: #000;
    margin: 0 auto 10%;
    padding: 50px;
}

.faq-title,.faq-title-jp{
    display: inline-block;
    color: #fff;
}
.faq-title{
    font-size: 40px;
    width: 10%;
}
.faq-title-jp{
    font-size: 20px;
    width: 80%;
    text-align: center;
}
/*------------------------*/
/*        contact         */
/*------------------------*/
.contact{
    background: url(../assets/img/contact-bg.jpg)center/cover no-repeat;

    padding: 10%;
}

.contact-title,.contact-title span,.contact-subtitle,.contact-text{
    color: #fff;
    text-align: center;
}

.contact-title,.contact-subtitle,.contact-text{
    margin-bottom: 40px;
}


.contact-btn{
    margin: 0 auto;
    background: none;
    border: 1px solid #fff;
    color: #fff;
}
</style>>