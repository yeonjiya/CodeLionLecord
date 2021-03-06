# CodeLionLecord
# <일단 만드는 HTML/CSS>

## HTML과 인사하기
 <가방2><가방1>내용물입니다.</가방1></가방2>
 
## CSS와 친해지기 
* html에는
``` <footer>copyright CODE LION. All rights reserved.</footer> ```

* css에는 
```
footer {
    text-align: center;
    background-color: black;
    color: white;
    }
 ```

## h1태그를 사용하여 자기소개하는 방법
```<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>자기 소개하기</title>
</head>
<body>
    <section>
        <h1>안녕하세요. 강연지입니다.</h1>
    </section>
</body>
</html>
```

## html 코드
``` <!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>강연지의 이력서</title>
  <link rel="stylesheet" href="codelion.css">
</head>
<body>
  <div class="mainbox">
    <div class="title-box">
      <h1>강연지</h1>
      <p class="name-text">HTML/CSS 개발자</p>
    </div>
    <section>
      <h2>ABOUT ME</h2>
      <p class="about-me-text">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
    </section>
    <section>
        <h2>EXPERIENCE</h2>
        <div class="float-wrap">
          <p class="title-text">Awesome Programming Company</p>
          <p class="year-text">2020 - Now</p>
        </div>
        <p class="desc-text">Front-End Web Developer</p>
        <p class="desc-subtext">HTML/CSS, JS, React, ...</p>
        <div class="float-wrap">
          <p class="title-text">Ministry of Health</p>
          <p class="year-text">2015 - 2018</p>
        </div>
        <p class="desc-text">UI/UX Designer</p>
        <p class="desc-subtext">Web design</p>
        <div class="float-wrap">
            <p class="title-text">Freelance Work</p>
            <p class="year-text">2011 - 2015</p>
        </div>
        <p class="desc-text">Graphic Designer</p>
        <p class="desc-subtext">Graphic Design, Editorial Design</p>
      </section>

      <section>
        <h2>ACTIVITIES</h2>
        <div class="float-wrap">
          <p class="title-text">Front-End Web Developer Forum Volunteer</p>
          <p class="year-text">2019 - 2020</p>
        </div>
        <p class="desc-text">Application Page Development</p>
        <p class="desc-subtext">Lorem ipsum dolor sit amet.</p>
        <div class="float-wrap">
          <p class="title-text">LIKELION SEOUL</p>
          <p class="year-text">2017 - 2018</p>
        </div>
        <p class="desc-text">Teacher in Mutsa University</p>
        <p class="desc-subtext">Lorem ipsum dolor sit amet.</p>
        <div class="float-wrap">
          <p class="title-text">Open Source Committer</p>
          <p class="year-text">2011 - 2013</p>
        </div>
        <p class="desc-text">Angular JS</p>
        <p class="desc-subtext">Lorem ipsum dolor sit amet.</p>
    </section>

    <section>
        <h2>EDUCATION</h2>
        <div class="float-wrap">
            <p class="title-text">Mutsa University</p>
            <p class="year-text">2008 - 2012</p>
        </div>
        <p class="desc-text">Computer Science and Engineering</p>
        <div class="float-wrap">
            <p class="title-text">Mutsa High school</p>
            <p class="year-text">2006 - 2008</p>
        </div>
        <p class="desc-text">Visual Communication Design</p>
        <div class="float-wrap">
            <p class="title-text">Online Programming Academy</p>
            <p class="year-text">2006 - 2007</p>
        </div>
        <p class="desc-text">Python Course</p>
    </section>

    <section>
      <h2>AWARDS</h2>
      <div class="float-wrap">
        <p class="title-text">LIKELION SEOUL</p>
        <p class="year-text">2018</p>
      </div>
      <p class="desc-text">Best Developer Award</p>
    </section>

    <div class="sns-wrap">
      <a href="http://facebook.com"><img class="sns-img" src="images/facebook.png"></a>
      <img class="sns-img" src="images/twitter.png">
      <img class="sns-img" src="images/linked-in.png">
      <img class="sns-img" src="images/insta.png">
    </div>
  </div>
  <footer>
      <p>Copyright CODE LION All rights reserved. </p>
  </footer>
</body>
</html>
```

## css 코드
``` 
@import url('https://fonts.googleapis.com/css?family=Montserrat:100,200,300,400,500,600,700,800&display=swap');

* {
    font-family: 'Montserrat';
}

body,h1,h2 {
    margin:0px;
    padding:0px;
}


body {
    min-width: fit-content;
}

h1 {
    font-size:36px;
    font-weight: bold;
    font-style: italic;
}


h2 {
    font-size:20px;
    color:#282828;
    font-weight: lighter;
    margin-bottom: 16px;
    border-bottom: 1px solid #ebebeb;
    padding-bottom: 5px;
}

.name-text {
    font-size:16px;
    color:#7c7c7c;
    font-weight: bold;
}

.about-me-text {
    font-size:10px;
    line-height: 16px;
}

.mainbox {
    width: 610px;
    padding: 30px;
    margin: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid #ebebeb;
    box-shadow: 0 1px 20px 0 rgba(0, 0, 0, 0.1);
}

.title-box {
    text-align: right;
}

section {
    margin-bottom:24px;
}

.float-wrap {
    overflow: hidden;
}

.title-text {
    font-size:11px;
    font-weight: bold;
    color: #282828;
    float: left;
}

.year-text{
    font-size:11px;
    font-weight: bold;
    color: #282828;
    float: right;
}

.desc-text {
    font-size: 9px;
}

.desc-subtext {
    font-size: 9px;
    color:#282828;
    padding-left:16px;
}

.sns-img {
    width:12px;
    height:12px;
}

.sns-wrap {
    text-align:right;
}

footer {
    text-align: center;
    background-color: #1e1e1e;
    padding: 20px;
    font-size: 12px;
    color: #919191;
}
```
