<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css">
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>

        <title>Complete Responsive Portfolio Website</title>
    </head>
    <body>

         <!-- HEADER -->
         <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">XAcad</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#service" class="nav__link">Services</a></li>
                        <li class="nav__item"><a href="#mywork" class="nav__link">My Work</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                    </ul>
                </div>

            </nav>
        </header>

        <main class="l-main">
            <!--===== HOME =====-->
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title">Hi,<br>I'am <span class="home__title-color">Web Developer</span> </h1>

                    <a href="#" class="button">Contact Me</a>
                </div>

                <div class="home__img">   
                    <img src="images/ppp.png" alt="">
                </div>
            </section>

            <!--===== ABOUT =====-->
            <section class="about section " id="about">
                <h2 class="section-title">About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img" >
                        <img src="images/pp.png" alt="">
                    </div>

                    <div>
                        <p class="about__text">LHello there! I'm Web Developer, a passionate and innovative web developer with a strong flair for crafting captivating online experiences. With a keen eye for design and a love for coding, I thrive on bringing ideas to life through the power of technology.
                        <br>
                        <br>
                        As a web developer, I specialize in designing and developing dynamic, user-centric websites that not only look visually stunning but also provide seamless functionality. From eye-catching landing pages to complex web applications, I take pride in every project I undertake. I am well-versed in various frontend and backend technologies, including HTML5, CSS3, JavaScript (ES6+), React, Node.js, and SQL databases, to name a few.
                        </p>           
                    </div>                                   
                </div>
            </section>

            <!--===== SERVICES =====-->
            <section class="service section" id="service">
                <h2 class="section-title">Services</h2>

                <div class="ag-format-container">
               <div class="ag-courses_box">
    <div class="ag-courses_item">
      <a href="#" class="ag-courses-item_link">
        <div class="ag-courses-item_bg"></div>

        <div class="ag-courses-item_title">
          Web Design  
        </div>

        <div class="ag-courses-item_date-box">
          <span class="ag-courses-item_date">
            <p>As a passionate and skilled web designer, I take great pride in creating visually stunning, user-friendly, and functional websites.I aim to deliver memorable online experiences that leave a lasting impression.</p>
          </span>
        </div>
      </a>
    </div>

    <div class="ag-courses_item">
      <a href="#" class="ag-courses-item_link">
        <div class="ag-courses-item_bg"></div>

        <div class="ag-courses-item_title">
            App Design 
        </div>

        <div class="ag-courses-item_date-box">
          <span class="ag-courses-item_date">
            <p>With a user-friendly interface, interactive elements, and a focus on visual aesthetics, the app will help users make a lasting impression on potential clients, collaborators, and employers.</p>
          </span>
        </div>
      </a>
    </div>

    <div class="ag-courses_item">
      <a href="#" class="ag-courses-item_link">
        <div class="ag-courses-item_bg"></div>

       <div class="ag-courses-item_title">
          UI/UX Design 
        </div>

        <div class="ag-courses-item_date-box">
          <span class="ag-courses-item_date">
            <p>The primary goal of the UI/UX design is to provide a seamless and intuitive experience for visitors to explore the portfolio,get a clear understanding, and easily navigate through the showcased projects.</p>
          </span>
        </div>
      </a>
    </div>
    </div>
      </section>

            <!--===== MY WORK =====-->
            <section class="work section" id="mywork">
                <h2 class="section-title">My Work</h2>

                <div class="work__container bd-grid">
                    <div class="work__img">
                        <img src="images/6.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="images/3.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="images/4.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="images/8.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="images/9.jpg" alt="">
                    </div>
                    <div class="work__img">
                        <img src="images/7.jpg" alt="">
                    </div>
                </div>
            </section>

            <!--===== CONTACT =====-->
            <section class="contact section" id="contact">
                <h2 class="section-title">Contact Me</h2>

                 <div class="home__social">
                    <a href="" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    <a href="" class="home__social-icon"><i class='bx bxl-behance' ></i></a>
                    <a href="" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                </div>

                <div class="contact__container bd-grid">
                    <form action="" class="contact__form">
                        <input type="text" placeholder="Name" class="contact__input">
                        <input type="mail" placeholder="Email" class="contact__input">
                        <textarea name="" placeholder="Message" id="" cols="0" rows="10" class="contact__input"></textarea>
                        <input type="button" value="Send" class="contact__button button">
                    </form>

                </div>

            </section>
        </main>

        <!--===== FOOTER =====-->
        <footer class="footer">
            <p class="footer__title">XAcademy</p>
            <div class="footer__social">
                <a href="#" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
                <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
            </div>
            <p>&#169; 2021 copyright all right reserved</p>
        </footer>
    </body>
</html>


@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&amp;display=swap");
/*===== VARIABLES CSS =====*/
:root{
  --header-height: 3rem;
  --font-semi: 600;
}

/*===== Colores =====*/
:root{
  --first-color:  #b36eda;
  --second-color: #0E2431;
}

/*===== Fuente y tipografia =====*/
:root{
  --body-font: 'Poppins', sans-serif;
  --big-font-size: 2rem;
  --h2-font-size: 1.25rem;
  --normal-font-size: 0.938rem;
}
@media screen and (min-width: 768px){
  :root{
    --big-font-size: 3.5rem;
    --h2-font-size: 2rem;
    --normal-font-size: 1rem;
  }
}

/*===== Margenes =====*/
:root{
  --mb-1: 0.5rem;
  --mb-2: 1rem;
  --mb-3: 1.5rem;
  --mb-4: 2rem;
  --mb-5: 2.5rem;
  --mb-6: 3rem;
}

/*===== z index =====*/
:root{
  --z-back: -10;
  --z-normal: 1;
  --z-tooltip: 10;
  --z-fixed: 100;
}

/*===== BASE =====*/
*,::before,::after{
  box-sizing: border-box;
}
html{
  scroll-behavior: smooth;
}
body{
  margin: var(--header-height) 0 0 0;
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  color: var(--second-color);

}
h1,h2,p{
  margin: 0;
}
ul{
  margin: 0;
  padding: 0;
  list-style: none;
}
a{
  text-decoration: none;
}
img{
  max-width: 100%;
  height: auto;
  display: block;
}
.l-main{
  background-color: #051522;
}
/*===== CLASS CSS ===== */
.section-title{
  position: relative;
  font-size: var(--h2-font-size);
  color: var(--first-color);
  margin-top: var(--mb-2);
  margin-bottom: var(--mb-4);
  text-align: center;
}
.section-title::after{
  position: absolute;
  content: "";
  width: 64px;
  height: 0.18rem;
  left: 0;
  right: 0;
  margin: auto;
  top: 2rem;
  background-color: var(--first-color);
}
.section{
  padding-top: 3rem;
  padding-bottom: 2rem;
}

/*===== LAYOUT =====*/
.bd-grid{
  max-width: 1024px;
  display: grid;
  grid-template-columns: 100%;
  grid-column-gap: 2rem;
  width: calc(100% - 2rem);
  margin-left: var(--mb-2);
  margin-right: var(--mb-2);

}
.l-header{
  width: 100%;
  position: fixed;
  top: 0;
  left: 0;
  z-index: var(--z-fixed);
  background-color:   #1d2b41;
  box-shadow: 0 1px 4px rgba(146,161,176,.15);
}

/*===== NAV =====*/
.nav{
  height: var(--header-height);
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-weight: var(--font-semi);
}
@media screen and (max-width: 768px){
  .nav__menu{
    position: fixed;
    top: var(--header-height);
    right: -100%;
    width: 80%;
    height: 100%;
    padding: 2rem;
    background-color: var(--second-color);
    transition: .5s;
  }
}
.nav__item{
  margin-bottom: var(--mb-4);
}
.nav__link{
  position: relative;

}
.nav__item a{
  color: white;
}
.nav__link:hover{
  position: relative;

}
.nav__link:hover::after{
  position: absolute;
  content: "";
  width: 100%;
  height: 0.18rem;
  left: 0;
  top: 2rem;
  background-color: var(--first-color);

}
.nav__item a:hover{
  color:  #b36eda;
  transition: .5 ease;

}
.nav__logo{
  color: var(--second-color);
}
.nav__toggle{
  color: var(--second-color);
  font-size: 1.5rem;
  cursor: pointer;
}

/*Active menu*/
.active::after{
  position: absolute;
  content: "";
  width: 100%;
  height: 0.18rem;
  left: 0;
  top: 2rem;
  background-color: var(--first-color);
}

/*=== Show menu ===*/
.show{
  right: 0;
}

/*===== HOME =====*/

.home{
  height: calc(100vh - 3rem);
  row-gap: 1rem;
}
.home__data{
  align-self: center;
}
.home__title{
  font-size: var(--big-font-size);
  margin-bottom: 10%;
  color: white;
}
.home__title-color{
  color: var(--first-color);
}
.home__social{
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.home__social-icon{
  width: max-content;
  margin-bottom: var(--mb-2);
  font-size: 1.5rem;
  color: var(--second-color);
}
.home__social-icon:hover{
  color: var(--first-color);
}
.home__img{
  position: absolute;
  right: 0;
  bottom: 0;
  width: 290px;
  background-image:url("images/b (2).png") ;
  background-size: cover;
}
.home__img img{
  width: 450px;
  height: 380px;
  transition: transform .2s ; /* Animation */

}
.home__img:hover{
  transition:.5s ease;
 transform: translate(-10px,-50px);
}
.home__img img:hover{
  transform: scale(1.3);
}

/*BUTTONS*/
.button{
  display: inline-block;
  background-color: var(--first-color);
  color: #fff;
  padding: .75rem 2.5rem;
  font-weight: var(--font-semi);
  border-radius: .5rem;
  margin-bottom: 200px;
}
.button:hover{
  box-shadow: 0 10px 36px rgba(0,0,0,.15);
}

/* ===== ABOUT =====*/
#about{
  margin-top: -6%;

}
.about__text{
  text-align: justify;
  color: white;
}
.about__container{
  row-gap: 2rem;
  text-align: center;
}
.about__subtitle{
  margin-bottom: var(--mb-2);
}
.about__img{
  justify-self: center;
  background-image: url("images/bb (2).png");
  background-size:cover;
  height: 499px;
  width: 540px;
  margin-left: -300px;

}
.about__img img
{
transform: scale(2.4);
margin-left: 250px;
margin-top: 80px;

}
.about__img:hover{
   transition: .5s;
 transform: translate(-10px,-20px);
}
.about__img img:hover{
 transition: .5s;
 transform: translate(-30px,-10px);
 transform: scale(2.9);
}
/* ===== SERVICES =====*/
.ag-format-container {
  width: 1142px;
  margin: 0 auto;
}
.ag-courses_box {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: start;
  -ms-flex-align: start;
  align-items: flex-start;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  padding: 50px 0;
}
.ag-courses_item {
  -ms-flex-preferred-size: calc(33.33333% - 30px);
  flex-basis: calc(33.33333% - 30px);
  margin: 0 15px 30px;
  overflow: hidden;
  border-radius: 28px;
}
.ag-courses-item_link {
  display: block;
  padding: 30px 20px;
  background-color: #121212;
  overflow: hidden;
  position: relative;
}
.ag-courses-item_link:hover,
.ag-courses-item_link:hover .ag-courses-item_date {
  text-decoration: none;
  color:#fff;
}
.ag-courses-item_link:hover .ag-courses-item_bg {
  -webkit-transform: scale(10);
  -ms-transform: scale(10);
  transform: scale(10);
}
.ag-courses-item_title {
  min-height: 87px;
  margin: 0 0 25px;

  overflow: hidden;

  font-weight: bold;
  font-size: 30px;
  color: #FFF;

  z-index: 2;
  position: relative;
}
.ag-courses-item_date-box {
  z-index: 2;
  position: relative;
}
.ag-courses-item_date {
  color: white;
  -webkit-transition: color .5s ease;
  -o-transition: color .5s ease;
  transition: color .5s ease
}
.ag-courses-item_date p{
  text-align: justify;
}
.ag-courses-item_bg {
  height: 128px;
  width: 128px;
  background-color:   #6f1bd3;
  z-index: 1;
  position: absolute;
  top: -75px;
  right: -75px;
  border-radius: 50%;
  -webkit-transition: all .5s ease;
  -o-transition: all .5s ease;
  transition: all .5s ease;
}
.ag-courses_item:nth-child(2n) .ag-courses-item_bg {
  background-color: #a9c6e5;
}
.ag-courses_item:nth-child(3n) .ag-courses-item_bg {
  background-color:var(--first-color);
}
.ag-courses_item:nth-child(4n) .ag-courses-item_bg {
  background-color: #952aff;
}
.ag-courses_item:nth-child(5n) .ag-courses-item_bg {
  background-color: #cd3e94;
}
.ag-courses_item:nth-child(6n) .ag-courses-item_bg {
  background-color:   #6f1bd3;
}



@media only screen and (max-width: 979px) {
  .ag-courses_item {
    -ms-flex-preferred-size: calc(50% - 30px);
    flex-basis: calc(50% - 30px);
  }
  .ag-courses-item_title {
    font-size: 24px;
  }
}

@media only screen and (max-width: 767px) {
  .ag-format-container {
    width: 96%;
  }

}
@media only screen and (max-width: 639px) {
  .ag-courses_item {
    -ms-flex-preferred-size: 100%;
    flex-basis: 100%;
  }
  .ag-courses-item_title {
    min-height: 72px;
    line-height: 1;

    font-size: 24px;
  }
  .ag-courses-item_link {
    padding: 22px 40px;
  }
  .ag-courses-item_date-box {
    font-size: 16px;
  }
}



/* ===== MY WORK =====*/
.work__container{
  row-gap: 2rem;
}
.work__img{
  box-shadow: 0 4px 25px rgba(14,36,49,.15);
  border-radius: .5rem;
  overflow: hidden;
}
.work__img img{
  transition: 1s;
  cursor: pointer;
  height: 250px;
  width: 350px;
}
.work__img img:hover{
  transform: scale(1.1);
}

/* ===== CONTACT =====*/
.contact__input{
  width: 100%;
  font-size: var(--normal-font-size);
  font-weight: var(--font-semi);
  padding: 1rem;
  border-radius: .5rem;
  border: 1.5px solid var(--second-color);
  outline: none;
  margin-bottom: var(--mb-4);
}
.contact__button{
  display: block;
  border: none;
  outline: none;
  font-size: var(--normal-font-size);
  cursor: pointer;
  margin-left: auto;
}

/* ===== FOOTER =====*/
.footer{
  background-color: var(--second-color);
  color: #fff;
  text-align: center;
  font-weight: var(--font-semi);
  padding: 2rem 0;
}
.footer__title{
  font-size: 2rem;
  margin-bottom: var(--mb-4);
}
.footer__social{
  margin-bottom: var(--mb-4);
}
.footer__icon{
  font-size: 1.5rem;
  color: #fff;
  margin: 0 var(--mb-2)
}

/* ===== MEDIA QUERIES=====*/
@media screen and (min-width: 768px){
  body{
    margin: 0;
  }
  .section{
    padding-top: 4rem;
    padding-bottom: 3rem;
  }
  .section-title{
    margin-bottom: var(--mb-6);
  }
  .section-title::after{
    width: 80px;
    top: 3rem;
  }

  .nav{
    height: calc(var(--header-height) + 1rem);
  }
  .nav__list{
    display: flex;
    padding-top: 0;
  }
  .nav__item{
    margin-left: var(--mb-6);
    margin-bottom: 0;
  }
  .nav__toggle{
    display: none;
  }
  .nav__link{
    color: var(--second-color);
  }

  .home{
    height: 100vh;
  }
  .home__data{
    align-self: flex-end;
  }
  .home__social{
    padding-top: 0;
    padding-bottom: 2.5rem;
    flex-direction: row;
    align-self: flex-end;
  }
  .home__social-icon{
    margin-bottom: 0;
    margin-right: var(--mb-4);
    color: white;
  }
  .home__img{
    width: 457px;
    bottom: 15%;
  }

  .about__container, .skills__container{
    grid-template-columns: repeat(2,1fr);
    align-items: center;
    text-align: initial;
  }
  .about__img img{
    width: 300px;
  }
  .work__container{
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2,1fr);
    column-gap: 2rem;
  }
  .contact__form{
    width: 360px;
  }
  .contact__container{
    justify-items: center;
  }
}

@media screen and (min-width: 1024px) {
  .bd-grid {
    margin-left: auto;
    margin-right: auto;
  }
  .home__img {
    right: 10%;
  }
}


    form{
     display: flex;
     flex-wrap: wrap;
    }
    .username{
      flex: 1 0 140px;
    }
    .email{
     flex: 1 0 140px;
    }
    .button{
      flex: 1 0 50px;
    }
