# goit-markup-hw-03

Goit Home work 03

<header class="nav">
      <div class="container nav-container">
      <nav class="head-nav">
        <a href="./index.html" class="logo" lang="en"><span class="web-logo">Web</span>Studio</a>
        <ul class="nav-links">
          <li class="item"><a href="./index.html" class="link current">Студия</a></li>
          <li class="item"><a href="./portfolio.html" class="link">Портфолио</a></li>
          <li class="item"><a href="#" class="link">Контакты</a></li>
        </ul>
      </nav>
      <ul class="contacts">
        <li class="item"><a href="mailto:info@devstudio.com" class="link contact">info@devstudio.com</a></li>
        <li class="item"><a href="tel:+380961111111" class="link contact">+38 096 111 11 11</a></li>
      </ul>
      </div>
    </header>

.container { width: 1200px; margin-left: auto; margin-right: auto; padding-left: 15px;
padding-right: 15px; outline: 2px solid tomato; }

/_ --Навигация-- _/

.section { padding-top: 96px; padding-bottom: 96px; }

.nav-container { display: flex; align-items: center; } .head-nav { display: flex; margin: 0; }

.nav-links { display: flex; margin: 0; margin-left: 93px; padding: 0; align-items: center; }

.head-nav .logo { padding-top: 24px; padding-bottom: 25px; }

.head-nav .item + .item { margin-left: 50px; }

.contacts .item + .item { margin-left: 50px; }

.contacts { display: flex; margin: 0;

margin-left: auto; padding: 0;
