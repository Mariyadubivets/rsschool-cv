<img src="https://github.com/Mariyadubivets/rsschool-cv/blob/gh-pages/cv_img.png" width="200">

# MARIYA DUBOVETS

Junior developer

## Contacts
1. E-mail: mariyadubovets@gmail.com
2. Instagram, Telegram: @marydubovets
3. Tel.: +375291863767
4. Mary Dubovets (@Mariyadubivets)

## Skills

- HTML, CSS (in progress);
- Communication, teamwork, flexibility, creativity;
- Version control system Git;
- GitLab;
- VS Code;
- Figma.

## About me
My name is Dubovets Mariya and I am the beginner developer. Right now I am learning Front-End at SkillBox courses. I have been studying HTML, CSS and working on the project - tourist's company web-site with a lot of hotel's offers. I desided to try out for this position because i like learning  and creating something new and Front-End is perfect for this. Hope it will be successful.

## Code examples (HTML/CSS)
```
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Отели</title>
    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="css/style.css">
</head>
<body class="body-back">
    <header class="header">
    <h1 class="vissually-hidden"> Сеть отелей Lagoona </h1>
        <div class="container">
          <div class="header-container flex">
            <a href="#" class="header-logo">
                <img src="img/logo.png" alt="logo">
            </a>
            <a href="tel:+74953225448" class="contact-header">
                +7 495 322-54-48
            </a>
            <a href="#" class="entrance-header">
              <svg class="header-svg" width="21" height="12" viewBox="0 0 21 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M10.59 1.41L14.17 5H0V7H14.17L10.58 10.59L12 12L18 6L12 0L10.59 1.41ZM19 0V12H21V0H19Z" fill="#CC9933"/>
                </svg>
                Личный кабинет
            </a>
          </div>
          <div class="flex header-div">
            <nav class="header-nav flex">
                <ul class="header-list list-reset flex">
                    <li class="header-list-item">
                        <a href="#about-us" class="header-nav-link">
                            О нас
                        </a>
                    </li>
                    <li class="header-list-item">
                        <a href="#services" class="header-nav-link">
                            Услуги
                        </a>
                    </li>
                    <li class="header-list-item">
                        <a href="#advantages" class="header-nav-link">
                            Преимущества
                        </a>
                    </li>
                    <li class="header-list-item">
                        <a href="#accommodation" class="header-nav-link">
                            Размещение
                        </a>
                    </li>
                    <li class="header-list-item">
                        <a href="#blog" class="header-nav-link">
                            Блог
                        </a>
                    </li>
                    <li class="header-list-item">
                        <a href="#contacts" class="header-nav-link">
                            Контакты
                        </a>
                    </li>
                </ul>
            </nav>
            <div class="flex">
            <button class="btn header-btn-tour">
                Хочу тур
            </button>
            <button class="btn header-btn-call">
                Обратный звонок
            </button>
          </div>
          </div>
          </div>
      </header>
    <main class="main">
        <section class="special-offers">
            <div class="container">
                <h2 class="section-title">
                    Спецпредложения
                </h2>
                <div class="special-offers-cards flex">
                    <div class="islands flex">
                        <div class="maldives island-card flex">
                            <h3 class="special-offers-cards-title">
                                Мальдивские острова
                            </h3>
                            <span class="special-offers-descr">
                                от 55 000
                            </span>
                            <a href="#" class="special-offers-link flex">
                                Подробнее
                                <svg class="arrow-islands" width="11" height="18" viewBox="0 0 11 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                  <path d="M1.49998 1.00002L9.27815 8.7782L1.49998 16.5564" stroke="#F0BF5F" stroke-width="2"/>
                                  </svg>
                            </a>
                        </div>
                        <div class="krit island-card flex">
                            <h3 class="special-offers-cards-title">
                                Горящий тур на&nbsp;остров Крит
                            </h3>
                            <span class="special-offers-descr">
                                от 30 000
                            </span>
                            <a href="#" class="special-offers-link flex">
                                Подробнее
                                <svg class="arrow-islands" width="11" height="18" viewBox="0 0 11 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                  <path d="M1.49998 1.00002L9.27815 8.7782L1.49998 16.5564" stroke="#F0BF5F" stroke-width="2"/>
                                  </svg>
                            </a>
                        </div>
                    </div>
                    <div class="luxe flex">
                        <h3 class="special-offers-cards-title lux-title">
                            Номера категории люкс
                        </h3>
                        <span class="special-offers-descr lux-descr">
                            от 5 000
                        </span>
                        <a href="#" class="special-offers-link flex">
                            Подробнее
                            <svg class="arrow-islands" width="11" height="18" viewBox="0 0 11 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                              <path d="M1.49998 1.00002L9.27815 8.7782L1.49998 16.5564" stroke="#F0BF5F" stroke-width="2"/>
                              </svg>
                        </a>
                    </div>
                </div>
            </div>
        </section>
```
```
html {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: inherit;
}

a {
  color: inherit;
  text-decoration: none;
}

img {
  max-width: 100%;
}

@font-face {
  font-family: 'Muller';
  src: url("../fonts/MullerRegular.woff2") format("woff2"),
  url("../fonts/MullerRegular.woff") format("woff");
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Muller';
  src: url("../fonts/MullerMedium.woff2") format("woff2"),
  url("../fonts/MullerMedium.woff") format("woff");
  font-weight: 500;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Muller';
  src: url("../fonts/MullerBold.woff2") format("woff2"),
  url("../fonts/MullerBold.woff") format("woff");
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}

body {
  min-width: 1170px;
  font-family: 'Muller', sans-serif;
  font-weight: 400;
}

/* globe */

.vissually-hidden {
  position: absolute;
  -webkit-clip-path: inset(100%);
  clip-path: inset(100%);
  overflow: hidden;
  margin: -1px;
  border: 0;
  padding: 0;
  width: 1px;
  height: 1px;
  white-space: nowrap;
  clip: rect(0 0 0 0);
}

.list-reset {
  margin: 0;
  padding: 0;
  list-style: none;
}

.flex {
  display: flex;
}
.container {
  width: 1170px;
  padding: 0;
  margin: 0 auto;
}

.section-title {
  margin: 0;
  font-weight: 400;
  font-size: 40px;
  line-height: 40px;
  color: #333333;
}

.body-back {
  background-color: #E5E5E5;
}

/* header */

.header-container {
  align-items: center;
  margin-bottom: 30px;
  width: 100%;
}

.header-logo {
  margin-right: 40px;
}

.contact-header {
  margin-right: auto;
  font-weight: 500;
  font-size: 20px;
  line-height: 20px;
  color: #666666;
}

.entrance-header {
  font-weight: 400;
  font-size: 16px;
  line-height: 16px;
  color: #CC9933;
}

.header-svg {
 transform: translateX(-5px);
}

.header-div {
  justify-content: space-between;
  align-items: center;
  padding: 14px 45px;
  background-color: #FFFFFF;
  border-radius: 15px;
}

.header-list-item:not(:last-child) {
  margin-right: 45px;
}

.header-list-item {
  font-weight: 400;
  font-size: 16px;
  line-height: 16px;
  color: #666666;
}

.btn {
  padding: 13px 20px;
  font-weight: 400;
  font-size: 16px;
  line-height: 16px;
  color: #CC9933;
  border: 1px solid #CC9933;
  border-radius: 10px;
  background-color: #FFFFFF;

}

.header-btn-tour {
  margin-right: 40px;
 }

 .header-btn-call {
  margin: auto;
 }

 .header {
  padding-top: 30px;
  margin-bottom: 70px;
 }

 /* special offers */

 .section-title {
  padding-left: 40px;
  margin-bottom: 20px;
 }

 .special-offers-cards {
  justify-content: space-between;
 }

 .islands {
 flex-direction: column;
 }

 .island-card {
  flex-direction: column;
  align-items: flex-start;
  width: 573px;
  min-height: 258px;
  padding: 40px 108px 40px 45px;
  background-repeat: no-repeat;
  background-size: cover;
  border-radius: 15px;
 }

 .maldives {
  margin-bottom: 24px;
  background-image: linear-gradient(90deg, rgba(48, 64, 89, 0.84) -2.9%, rgba(53, 65, 83, 0) 65.7%), url("../img/Maldives.jpg");
 }

 .krit {
  background-image: linear-gradient(90deg, rgba(48, 64, 89, 0.84) -2.9%, rgba(53, 65, 83, 0) 65.7%), url('../img/Krit.jpg');
 }

 .special-offers-cards-title {
  margin: 0;
  margin-bottom: 15px;
  font-weight: 700;
  font-size: 40px;
  line-height: 40px;
  color: #FFFFFF;
 }

 .special-offers-descr {
  margin-bottom: 47px;
  font-weight: 400;
  font-size: 20px;
  line-height: 20px;
  color: #FFFFFF;
  opacity: .8;
 }

 .special-offers-link {
  font-weight: 400;
  font-size: 16px;
  line-height: 16px;
  color: #F0BF5F;
 }

 .arrow-islands {
  transform: translateX(7px);
 }

 .luxe {
  flex-direction: column;
  align-items: flex-start;
  max-width: 573px;
  min-height: 540px;
  width: 100%;
  padding: 212px 229px 40px 45px;
  background-image: url('../img/lux.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  border-radius: 15px;
 }

 .lux-title {
  font-weight: 700;
  font-size: 60px;
  line-height: 60px;
 }

 .lux-descr {
  font-weight: 400;
  font-size: 30px;
  line-height: 30px;
 }

 .special-offers {
  margin-bottom: 70px;
 }
```
## Eperiences
I have no experinces at IT sphere. My project at SkillBox in progress, but small part of these codes are above.

## Education

Belarusian State University, Faculty of law. Bachelor, 2018г.

## English skills

English (B2 in progress), write (B1 in progress).
I use English mainly for traveling (Austia, Italy, Spain, Czech Republic, Turkey, Poland, Sweden) and as the language for communication with foreign friends from Italy.
