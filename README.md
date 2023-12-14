<style>
    .App{
    text-align: center;
    }
    
    .App::before {
    content: "";
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: radial-gradient(circle, #62d7eb, #00CED1, #008B8B, #008B8B, #191970, #000000);
    background-size: 100% 100%;
    animation: ondas 10s ease-in-out infinite, parpadeo 15s infinite;
    pointer-events: none;
    }

    @keyframes ondas {
    0% {
        background-position: 0% 0%;
    }
    25% {
        background-position: 0% 0%;
    }
    50% {
        background-size: 120% 120%;
        background-position: 100% 0%;
    }
    75% {
        background-position: 100% 0%;
    }
    100% {
        background-size: 100% 100%;
        background-position: 0% 0%;
    }
    }

    @keyframes parpadeo {
    0%, 25%, 50%, 75%, 100% {
        opacity: 0.4;
    }
    12.5%, 37.5%, 62.5%, 87.5% {
        opacity: 0.08;
    }
    } 

    .texto {
      position: relative;
      font-size: 24px;
      display: inline-block;¿
    }

    .texto span {
      transition: color 0.5s ease-in-out;
    }

    .texto:hover span:nth-child(1) {
      color: #1E4094; /* Azul */
    }

    .texto:hover span:nth-child(2) {
      color: white;
    }

    .texto:hover span:nth-child(3) {
      color: #CE1126; /* Rojo */
    }

    .texto:hover span:nth-child(4) {
      color: white;
    }

    .texto:hover span:nth-child(5) {
      color: #1E4094; /* Azul */
    }

    .tools-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .tools-container a {
      margin: 10px;
      padding: 10px;
      background-color: white;
      border-radius: 5px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-decoration: none;
      transition: background-color 0.3s ease-in-out;
      --color: #333;
      --hover: #8ed9f5;
      color: var(--color);
    }

    .tools-container a:hover, .tools-container a:focus  {
        background-color: #e0e0e0;
        border-color: var(--hover);
        color: #000;
        box-shadow: 0 0.5em 0.5em -0.4em var(--hover);
        transform: translateY(-0.25em);
    }

    .tools-container img {
      width: 40px;
      height: 40px;
      margin-bottom: 5px;
    }
</style>
<div class="fondo">
<div class= "App">
    <h1 align="center">Hey there world! 👋 Meet the creative force that is Kevin Salazar.</h1>
    <h3 align="center">Embracing the <span class="texto"><span>pu</span><span>r</span><span>a v</span><span>i</span><span>da</span></span> spirit from the heart of Costa Rica, I bring a vibrant blend of dedication and passion to the world of full-stack development. 
    With a zest for innovation and a commitment to excellence, I'm not just a coder, I'm a creator weaving digital dreams into reality!</h3>
<p align="center"> <img src="https://komarev.com/ghpvc/?username=kevin-salazar-itcr&label=Profile%20views&color=0e75b6&style=flat" alt="kevin-salazar-itcr" /> </p>

<p align="center"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=kevin-salazar-itcr" alt="kevin-salazar-itcr" /></a> </p>

🌱 I’m currently learning <a href="https://www.php.net/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-plain.svg" alt="php" width="40" height="40"/> </a> <a href="https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/objectivec/objectivec-plain.svg" alt="objective-c" width="40" height="40"/> </a> 

👨‍💻 Feel free to explore all my projects at your leisure: [https://github.com/Kevin-Salazar-itcr](https://github.com/Kevin-Salazar-itcr)

📫 Don't you wanna check out my private repos? Hit me up. **ksalaz1032019@gmail.com**

⚡ Fun fact: **I'm a creative force with an unwavering dedication to my craft.**

<h3 align="center">Connect with me:</h3>
<p align="center">
<a href="https://www.facebook.com/kevin.salazarvalle.5/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="kevin salazar valle" height="30" width="40" /></a>
<a href="https://instagram.com/k_salaz21" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="k_salaz21" height="30" width="40" /></a>
<a href="coming soon" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="coming soon" height="30" width="40" /></a>
<a href="https://discord.gg/kevin_s23085" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="kevin_s23085" height="30" width="40" /></a>

</p>

<h3 align="center">Languages and Tools:</h3>
<div class="tools-container">
    <a href="https://angular.io" target="_blank" rel="noreferrer">
      <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular"/>
      Angular
    </a>
    <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer">
      <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash"/>
      Bash
    </a>
    <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap"/>
      Bootstrap
    </a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> C </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> C++</a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> C#</a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> CSS</a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/>Django </a> <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> .Net</a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/>Express </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>Figma </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>Git </a> <a href="https://www.haskell.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1c/Haskell-Logo.svg" alt="haskell" width="40" height="40"/> Haskell </a> <a href="https://heroku.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> Heroku</a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> HTML </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> Java</a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> Javascript</a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> Linux</a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> MongoDB</a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> MSSQL </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> MySQL</a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> Node.js</a> <a href="https://www.oracle.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> Oracle</a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> Pandas</a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/>Photoshop </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> PostgreSQL</a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> Python</a> <a href="https://www.qt.io/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Qt_logo_2016.svg" alt="qt" width="40" height="40"/>Qt </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>React </a> <a href="https://www.rust-lang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" width="40" height="40"/>Rust </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> Scikit_learn</a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> Seaborn</a> <a href="https://www.selenium.dev" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> Selenium</a> <a href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40"/> SQLite</a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> Tensorflow</a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> Typescript</a>
</div>
</br>
<h3 align="center">Wanna see my stats?</h3>
<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=kevin-salazar-itcr&show_icons=true&locale=en&layout=compact" alt="kevin-salazar-itcr" /></p>

<p><img align="left" src="https://github-readme-streak-stats.herokuapp.com/?user=Kevin-Salazar-itcr&" alt="Kevin-Salazar-itcr" /></p>

<p>&nbsp;<img align="right" src="https://github-readme-stats.vercel.app/api?username=kevin-salazar-itcr&show_icons=true&locale=en" alt="kevin-salazar-itcr" /></p>

<h2 align="center">See you next time!</h3>

</div>
</div>
