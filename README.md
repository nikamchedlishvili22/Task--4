<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Home Page</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="header">
      <header>
        <img class="box" src="photo/logo.png" alt="" />
        <p class="book">წიგნები</p>
        <p class="autor">ავტორები</p>
        <p class="shesaxeb">ჩვენს შესახებ</p>
        <p class="blog">ბლოგი</p>
        <p class="contact">კონტაქტი</p>
      </header>
    </div>
    <main>
      <div class="backgroundimg">
        <img src="photo/background image.png" alt="" />
      </div>
      <section class="aside">
        <img class="frame1" src="photo/Frame 1.svg" alt="" />
        <h5>ქალები ლიტერატურაში</h5>
        <article>
          <p class="article">თამათა მელაშვილი</p>
          <p class="article2">შაშვი შაშვი მაყვალი</p>
          <p class="article3">8,90 ლ</p>
          <p class="article4">ეკა ქევანიშვლი</p>
          <p class="article5">
            ღარიბების ტრანსპორტი არსად <br />
            გაჩერდება
          </p>
          <p class="article6">12,70 ლ</p>
          <p class="article7">ზაირა არსენიშვილი</p>
          <p class="article8">ვა სოფელო...</p>
          <p class="article9">18 ლ</p>
        </article>
        <img class="foto1" src="photo/tamta melashvili.png" alt="tamta" />
        <img class="foto2" src="photo/eka qevanishvili.png" alt="eka" />
        <img class="foto3" src="photo/zaira arsenishvili.png" alt="zaira" />
      </section>
      <section class="frame">
        <img src="photo/Frame 1.png" alt="" />
        <p class="kviris">კვირის ავტორები</p>
        <div class="human">
          <img class="girl" src="photo/girl photo.png" alt="first girl" />
          <img class="man" src="photo/men photo.png" alt="first man" />
          <img class="girl2" src="photo/girl photo2.png" alt="" />
          <img class="man2" src="photo/men photo2.png" alt="" />
        </div>
      </section>
    </main>
  </body>
  <footer class="footerbackground">
    <p class="kontaqti">კონტაქტი</p>
    <p class="magaziebi">მაღაზიები</p>
    <p class="kitxva">კითხვა/პასუხი</p>
    <img class="facebook" src="photo/facebook.svg" alt="" />
    <img class="youtube" src="photo/fe_youtube.svg" alt="" />
    <img class="linkedin" src="photo/bxl_linkedin.svg" alt="" />
    <img class="instagram" src="photo/ph_instagram-logo-light.svg" alt="" />
  </footer>
</html>


.header {
    overflow: hidden;
    background-color: #D9D9D9;
    padding: 20px;
    width: 1280px;
    height: 100px;
}
p {
    position: absolute;
    top: 70px;
    width: 90px;
    height: 30px;
    text-align: center;
    display: flex;
    text-decoration: none;
    padding: 0 100px;
    margin: 0 575px;
    font-family: 'alk_life';
}
.box {
    width: 178px;
    height: 100px;
    padding: 0 130px;
}
@font-face {
    font-family: 'alk_life';
    src: url(alk_life.otf);
}
.book {
    font-size: 20px;
    color: #A62B28;
}
.autor {
    position: absolute;
    top: 70px;
    width: 117px;
    height: 30px;
    padding: 0 200px;
    font-size: 20px;
    color: #717276;
}
.shesaxeb {
    display: flex;
    position: absolute;
    width: 163px;
    height: 30px;
    top: 70px;
    padding: 0 320px;
    font-size: 20px;
    color: #717276;
}
.blog {
    position: absolute;
    width: 163px;
    height: 30px;
    top: 70px;
    padding: 0 470px;
    font-size: 20px;
    color: #717276;
}
.contact {
    position: absolute;
    width: 109px;
    height: 30px;
    top: 70px;
    padding: 0 550px;
    font-size: 20px;
    color: #717276;
}
.backgroundimg {
    position: absolute;
    top: 300px;
    display: flex;
    width: 1180px;
    height: 287px;
    padding: 30px;
    margin: 0 5px;
}
.aside {
    position: absolute;
    top: 800px;
    width: 100px;
    height: 100px;
}
h5 {
    display: flex;
    position: absolute;
    top: 2px;
    width: 393px;
    height: 40px;
    padding: 0 160px;
    font-size: 32px;
    font-family: 'bpg_dejavu_sans';
    color: #717276;
}
.foto1 {
    position: absolute;
    display: flex;
    width: 380px;
    height: 686px;
    top: 150px;
    padding: 0 40px;
}

.foto2 {
    position: absolute;
    display: flex;
    width: 380px;
    height: 686px;
    top: 150px;
    padding: 0 450px;
}

.foto3 {
    position: absolute;
    display: flex;
    width: 380px;
    height: 686px;
    top: 150px;
    padding: 0 860px;
}
@font-face {
    font-family: 'bpg_dejavu_sans';
    src: url(bpg_dejavu_sans.otf);
}
.article {
    text-decoration: none;
    text-align: left;
    position: absolute;
    display: flex;
    width: 238.39px;
    height: 39px;
    top: 850px;
    margin: 0 5px;
    font-family: 'bpg_dejavu_sans';
    color: #717276;
    font-size: 24px;
}

.article2 {
    text-align: left;
    display: flex;
    position: absolute;
    width: 260.8px;
    height: 30px;
    top: 900px;
    margin: 0 1px;
    color: black;
    font-size: 24px;
}
.article3 {
    text-align: center;
    display: flex;
    position: absolute;
    width: 95.76px;
    height: 39px;
    top: 940px;
    margin: 0 70px;
    color: #000000;
    font-family: 'bpg_dejavu_sans';
    font-size: 24px;

}

.article4 {
    text-decoration: none;
    text-align: center;
    position: absolute;
    width: 212px;
    height: 49px;
    top: 850px;
    left: 530px;
    padding: 0 5%;
    margin: 0 20px;
    font-family: 'bpg_dejavu_sans';
    color: #717276;
    font-size: 24px;
}

.article5 {
    display: flex;
    position: absolute;
    width: 380px;
    height: 60px;
    top: 800px;
    padding: 100px;
    margin: 0 360px;
    font-size: 24px;
}

.article6 {
    position: absolute;
    width: 112.78px;
    height: 39px;
    top: 970px;
    margin: 0 400px;
    padding: 0 210px;
    color: black;
    font-family: 'bpg_dejavu_sans';
}

.article7 {
    position: absolute;
    width: 253.46px;
    height: 39px;
    top: 760px;
    padding: 90px;
    margin: 0 865px;
    font-family: 'bpg_dejavu_sans';
    color: #717276;
    font-size: 24px;
}

.article8 {
    position: absolute;
    width: 158.79px;
    height: 30px;
    top: 600px;
    padding: 300px;
    font-size: 24px;
    margin: 0 700px;
}

.article9 {
    position: absolute;
    width: 69.22px;
    height: 39px;
    top: 350px;
    padding: 600px;
    font-size: 24px;
    margin: 0 450px;
    font-family: 'bpg_dejavu_sans';

}
.frame {
    position: absolute;
    width: 100px;
    height: 100px;
    padding: 30px;
    top: 1800px;
}

.frame1 {
    position: absolute;
    width: 100px;
    height: 100px;
    padding: 30px;
}
.kviris {
    position: absolute;
    width: 292px;
    height: 51px;
    top: 1px;
    padding: 70px;
    margin: 0 60px;
    font-size: 24px;
    color: #717276;
    font-family: 'bpg_dejavu_sans';
}
.man {
    position: absolute;
    width: 280px;
    height: 260px;
    top: 140px;
    padding: 30px;
    margin: 0 310px;
}
.girl {
    position: absolute;
    width: 280px;
    height: 260px;
    top: 170px;
    margin: 0 50px;
}

.girl2 {
    position: absolute;
    width: 280px;
    height: 260px;
    top: 170px;
    margin: 0 630px;
}
.man2 {
    position: absolute;
    width: 280px;
    height: 260px;
    top: 170px;
    margin: 0 920px;
}
.kontaqti {
    position: absolute;
    width: 109px;
    height: 30px;
    top: 60px;
    padding: 10px;
    margin: 0 50px;
    display: flex;
    font-size: 24px;
    color: black;
}
.footerbackground {
    position: absolute;
    background-color: #D9D9D9;
    width: 1280px;
    height: 200px;
    top: 2400px;
}

.magaziebi {
    position: absolute;
    width: 126px;
    height: 30px;
    top: 80px;
    padding: 30px;
    font-size: 24px;
    margin: 0 30px;
}

.kitxva {
    position: absolute;
    width: 171px;
    height: 30px;
    top: 140px;
    padding: 10px;
    margin: 0 45px;
    font-size: 24px;
}
.facebook {
    position: absolute;
    width: 30px;
    height: 30px;
    top: 70px;
    margin: 0 85%;
}
.youtube {
    position: absolute;
    width: 30px;
    height: 30px;
    top: 70px;
    margin: 0 89%;
}
.linkedin {
    position: absolute;
    width: 30px;
    height: 30px;
    top: 70px;
    margin: 0 93%;
}
.instagram {
    position: absolute;
    width: 30px;
    height: 30px;
    top: 70px;
    margin: 0 96%;
}
