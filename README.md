<!DOCTYPE html>
<html>
    <head>
        <title>Image Gallery</title>
    </head>
    <style>
        .sub img{
    height:130px;
    width:150px;
    border-top-left-radius: 9px;
    border-top-right-radius: 9px;
}
.sub{
    display:flex;
    flex-direction: column;
    align-items: center;
    width: 150px;
    height:30vh;
    background-color: rgb(155, 16, 189);
    box-shadow:0px 3px 10px;
    border-radius: 9px;
    border:1px solid blue ;
    transition: transform 0.3s ease;
    margin-right:1%;
}
.main{
    margin-top: 6%;
    display: flex;
    gap:20px;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-left: 2%;
}
.sub:hover{
        transform: scale(1.1);
}
h1{
    text-align: center;
    color: rgb(251, 230, 73);
    background-color: rgb(164, 50, 206);
    margin: 0;
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
}
    </style>
    <body>
        <h1>K-Actors</h1>
        <div class="main">
        <div class="sub">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTajw3L96I0fznUO2BppwRtKpcntJvq0X8LVA&s">
            <h3>Kim So Hoon</h3>
        </div>
        <div class="sub">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlO_5uAm0C5ilyYFdEyIJBAb7EEDRLQW_DxA&s">
            <h3>Kim ji woon</h3>
        </div>
        <div class="sub">
            <img src="https://netfonix.com/wp-content/uploads/2024/05/Kim-Hye-yoon.jpg">
            <h3>Kim Hyun</h3>
        </div>
        <div class="sub">
            <img src="https://www.sportschosun.com/images/2024/08/14/jung-hae-in-first-rocco-challenge-are-you-nervous-11443/jung-hae-in-first-rocco-challenge-are-you-nervous-1144301.jpg">
            <h3>Haein ho</h3>
        </div>
        <div class="sub">
            <img src="https://inkistyle.com/wp-content/uploads/2024/08/240814-Jung-So-Min-Fashion-Love-Next-Door-Press-Conference-1-683x1024.jpg">
            <h3>So min Jung</h3>
        </div>
        <div class="sub">
            <img src="https://img.koreaboo.com/tr:n-thumb_mega/2024/05/post1-2024-05-16T121335.570.jpg">
            <h3>Byun woo seok</h3>
        </div>
        <div class="sub">
            <img src="https://i0.wp.com/www.fashionchingu.com/wp-content/uploads/2022/02/true-beauty-im-jukyung-feminine-school-uniform.jpg">
            <h3>Ju Kyung</h3>
        </div>
        <div class="sub">
            <img src="https://i.pinimg.com/736x/fe/ac/1b/feac1b6f0024ee585025026459be591e.jpg">
            <h3>Hwag in hoop</h3>
        </div>
        <div class="sub">
            <img src="https://img.koreaboo.com/tr:n-thumb_mega/2024/05/post1-2024-05-16T121335.570.jpg">
            <h3>Byun woo seok</h3>
        </div>
        <div class="sub">
            <img src="https://i0.wp.com/www.fashionchingu.com/wp-content/uploads/2022/02/true-beauty-im-jukyung-feminine-school-uniform.jpg">
            <h3>Ju Kyung</h3>
        </div>
        <div class="sub">
            <img src="https://i.pinimg.com/736x/fe/ac/1b/feac1b6f0024ee585025026459be591e.jpg">
            <h3>Hwag in hoop</h3>
    </div>
    <div class="sub">
        <img src="https://netfonix.com/wp-content/uploads/2024/05/Kim-Hye-yoon.jpg">
        <h3>Kim  Hyun</h3>
    </div>
    <div class="sub">
        <img src="https://www.sportschosun.com/images/2024/08/14/jung-hae-in-first-rocco-challenge-are-you-nervous-11443/jung-hae-in-first-rocco-challenge-are-you-nervous-1144301.jpg">
        <h3>Haein ho</h3>
    </div>
    <div class="sub">
        <img src="https://inkistyle.com/wp-content/uploads/2024/08/240814-Jung-So-Min-Fashion-Love-Next-Door-Press-Conference-1-683x1024.jpg">
        <h3>So min Jung</h3>
    </div>
    <div class="sub">
        <img src="https://netfonix.com/wp-content/uploads/2024/05/Kim-Hye-yoon.jpg">
        <h3>Kim Hyun</h3>
    </div>
    <div class="sub">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTlO_5uAm0C5ilyYFdEyIJBAb7EEDRLQW_DxA&s">
        <h3>Kim ji woon</h3>
    </div>
    <div class="sub">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRk3pI5SpAVZiSNnMwSDw-jTYKiDfBSxWBqjw&s">
        <h3>Kim so Hyun</h3>
    </div>
    <div class="sub">
        <img src="https://www.sportschosun.com/images/2024/08/14/jung-hae-in-first-rocco-challenge-are-you-nervous-11443/jung-hae-in-first-rocco-challenge-are-you-nervous-1144301.jpg">
        <h3>Haein ho</h3>
    </div>
        </div>
    </body>
</html>
