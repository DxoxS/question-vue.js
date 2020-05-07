<template>
  <div id="app">
    <router-view/>
  </div>
</template>
<script></script>
<style>
@charset "UTF-8";

/*
html5doctor.com Reset Stylesheet
v1.6.1
Last Updated: 2010-09-17
Author: Richard Clark - http://richclarkdesign.com
Twitter: @rich_clark
*/

html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1.6;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}
/* リセットCSS */


html{
    height: 100%;
}


a{
    color: #333333;
    text-decoration: none;
}
img{
    width: 100%;
    height: 100%;
    display: block;
}

.flex{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
body{
    color: #333333;
    height: 100%;
}

.mgb-15{
    margin-bottom: 15px;
}

.common-btn{
    display: block;
    width: 130px;
    height: 40px;
    line-height: 40px;
    background: #fff;
    padding: 0 20px;
    color: #000;
    text-align: center;
}

.section-title{
    font-size: 40px;
    line-height: 1;
}

.section-title span{
    font-size: 20px;
}

/*
.fadein {
    opacity: 0;
    transform: translate(0, 200px);
    transition: all 1s;
    -webkit-transform: translate(0, 200px);
    -moz-transform: translate(0, 200px);
    -ms-transform: translate(0, 200px);
    -o-transform: translate(0, 200px);
}

.fadein.scrollIn{
    opacity : 1;
    transform : translate(0, 0);
}

*/

</style>