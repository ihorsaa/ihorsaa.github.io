
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Суперкомп'ютер</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div id="top">
    <h1>Суперкомп'ютер</h1>
    <h3>Суперкомп’ютер для сучасних технологій</h3>
  </div>

  <div id="main">
    <div class="intro">
      <h2>Суперкомп'ютер</h2>
      <span>У сучасному світі суперкомп'ютери стали робочим інструментом в наукових дослідженнях та інженерних розрахунках. Академік РАН Веліхов Е. П. назвав їх основною технологічною зброєю XXI ст.</span>
    </div>
    <div class="text">
      <span>Сучасний комп’ютер - це складний комплекс технічного і математичного забезпечення. Слід відзначити, отже, що створення згаданих комп’ютерів здійснювалось нами паралельно з розробкою відповідного програмно-функціонального забезпечення, що дає можливість ефективно розв’язувати досить складні задачі.</span>
    </div>
  </div>

  <div id="overview">
    <h2>Чим принципово відрізняється розв’язування задач на суперкомп’ютері від того, як це відбувається на комп’ютерах звичайних?</h2>
    <span>Обчислювальний процес на суперкомп’ютері можна проводити як розпаралелену дію - коли розв’язання складної задачі, згідно з певним математичним методом, розбивається на паралельні гілочки, реалізація кожної з яких може здійснюватися окремо на одному з процесорів суперкомп’ютера. Отож, якщо ми маємо, скажімо, 64 процесори і алгоритм розв’язання задачі може бути розбитий на 64 незалежні гілочки, то час розв’язування задачі, порівняно з тим, яким би він був, коли б її розв’язували на комп’ютері звичайному, зменшиться приблизно в 64 рази. Приблизно, оскільки, як правило, прискорення буває трохи меншим, і ось чому: певний час витрачається суперкомп’ютером на організацію обчислювального процесу, зокрема на обмін інформацією, що відбувається між окремими процесорами. В деяких випадках, нечастих, можна сказати, екзотичних, саме ця обставина — обміну інформацією між окремими гілочками — дає несподіваний ефект, прискорення збільшується.</span>
    

  </div>
  <div id="another">
    <h6>Де можна застосувати суперкомп’ютер уже тепер?</h6>
    <span>Конструкція суперкомп’ютера передбачає користування його можливостями як безпосередньо, так і на відстані, наприклад, із допомогою системи Інтернет. Сфера застосування — передусім там, де потрібна надшвидкісна чи регулярна і термінова обробка великих масивів даних, пов’язана з великим обсягом обчислень. Як правило, ця обробка даних зводиться до необхідності розв’язання складних задач великої розмірності (сотні тисяч чи десятки мільйонів змінних і такого ж порядку кількість обмежень). Це і задачі оптимізаційного плану розвитку економіки країни чи окремого регіону, наприклад, задачі оптимізаційного управління складними об’єктами, задачі проектування складних споруд чи процесів (проектування технологічних процесів, супутників, атомних станцій та ін.), проблеми вибору найкращих шляхів розвитку бізнесу чи, скажімо, задачі розшифровки генома людини. Цей перелік важливих задач можна продовжити, він практично безмежний. 
      <br> Важливо те, що вже сьогодні зазначені задачі ми можемо ефективно розв’язувати, оскільки тепер маємо сучасні власні суперкомп’ютери, відповідні математичні моделі та методи.</br>
    </span>
    </div>
  <div id="contacts">
    <center><h5>Зворотній зв'язок</h5></center>
    <form id="form_input">

      <label for="name">Ім'я <span></span></label><br>

      <input type="text" placeholder="Ваше ім'я" name="name" id="name"><br>

      <label for="email">Ваша пошта <span></span></label><br>

			<input type="email" placeholder="Ваша пошта" name="email" id="email"><br>

			<label for="message">Повідомлення <span></span></label><br>

			<textarea placeholder="Ваше повідомлення" name="message" id="message"></textarea><br>

			<div id="mess_send" class="btn">Відправити</div><br><br>

      <label for="outputEmail">Моя пошта</label><br>

      <input type="text" name="outputEmail"placeholder="ihorsavich@gmail.com" disabled="">
    </form>
  </div>

  
</body>
</html>



* {
  margin: 0;
  padding: 0;
  outline: none;
}

body, html {
  width: 100%;
  height: 100%;
}

body {
  background-color: #0000FF;
  font-family: Trebuchet MS, Helvetica;
}





@media (min-width: 701px) {
  #logo {
    float: left;
    width: 30%;
    font-size: 1.1em;
  }

  #about {
    float: right;
    width: 67%;
  }
}

@media (max-width: 700px) {
  #logo {
    margin-top: 15px;
    width: 100%;
    font-size: 1.5em;
  }

  #about {
    float: left;
    width: 100%;
  }
}

#about {
  text-align: center;
  font-size: 1em;
  line-height: 40px;
  margin-bottom: 10px;
}

#about > a {color: #fff}

#about > a:hover {
  color: #b0b0b0;
  text-decoration: underline;
}

#about > a:not(:last-child) {
  margin-right: 7%;
}



.fixed {
  z-index: 5000;
  background-color: #fff;
  border-bottom: 1px solid silver;
}


.fixed #about a {color: #343434}
.fixed #about a:hover {color: #7c7c7c}



#top {
  width: 100%;
  background-image: url(https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/IBM_Blue_Gene_P_supercomputer.jpg/1200px-IBM_Blue_Gene_P_supercomputer.jpg);
  background-blend-mode: multiply;
  background-color: #2e3a44;
  background-size: cover;
  text-align: center;
  color: #F0F8FF;
}

@media (min-width: 1001px) {
  #top {
    font-size: 3em;
    height: 1000px;
  }
}

@media (max-width: 1000px) and (min-width: 651px) {
  #top {
    font-size: 2em;
    height: 600px;
  }
}

@media (max-width: 650px) {
  #top {
    font-size: 1.3em;
    padding-top: 50%;
    height: 500px;
  }
}

@media (max-width: 450px) {
  #top {
    font-size: 0.9em;
  }
}

#top h1 {
  padding-top: 20%;
}

#top h3 {
  color: #ccc;
}


#main {
  float: left;
  background-color: #f6f6f6;
  border-top: 2px solid silver;
  color: #191970;
  font-size: 1.3em;
}

@media (min-width: 1401px) {
  #main {
    padding: 100px 20%;
    width: 60%;
  }
}

@media (max-width: 1400px) {
  #main {
    padding: 100px 10%;
    width: 80%;
  }
}

@media (max-width: 700px) {
  #main div {
    width: 98%!important;
    margin-bottom: 20px;
  }
}

#main div {
  width: 48%;
  margin-right: 2%;
  float: left;
}

#main h2 {font-size: 3em}
#main span {color: #00BFFF}



#overview {
  float: left;
  background-image: url(https://habrastorage.org/webt/sm/pr/yk/smpryksy71gun5aikxawvme5gqq.jpeg);

  background-blend-mode: multiply;
  background-color: #403f40;
  background-size: cover;
  background-attachment: fixed;

  padding: 100px 0;
  width: 100%;
  text-align: center;
  color: #fff;
}

#overview h2 {font-size: 4em}
#overview h4 {color: #ccc; font-size: 1.5em}
#overview .img {
  float: left;
  width: 30%;
  margin-right: 5%;
  margin-top: 50px;
}

#overview .img:nth-child(odd) {
  margin-left: 18%;
}
#overview img {
  background: #fafafa;
  padding: 5px;
  border: 2px solid silver;
  float: left;
  width: 100%;
  max-width: 500px;
}
#overview span {
  float: left;
  width: 100%;
  font-size: 1.3em;
  margin-top: 10px;
}
#another {
  float: left;
  background-image: url(https://znaj.ua/crops/4682f1/620x0/1/0/2018/12/21/2h6o5sgPRsGiFYhby0GyYvYrrCdPJBXE37ctiaHf.jpeg);

  background-blend-mode: multiply;
  background-color: #403f40;
  background-size: cover;
  background-attachment: fixed;

  padding: 100px 0;
  width: 100%;
  text-align: center;
  color: #fff;
}

#another h6 {font-size: 4em}
#another h4 {color: #ccc; font-size: 1.5em}


#another .img {
  float: left;
  width: 30%;
  margin-right: 5%;
  margin-top: 50px;
}

#another .img:nth-child(odd) {
  margin-left: 18%;
}

#another img {
  background: #fafafa;
  padding: 5px;
  border: 2px solid silver;
  float: left;
  width: 100%;
  max-width: 500px;
}

#another span {
  float: left;
  width: 100%;
  font-size: 1.3em;
  margin-top: 10px;
}




#contacts {
  width: 100%;
  float: left;
  padding-bottom: 40px;
  padding-top: 70px;
  border-top: 4px solid #ccc;
  background: #f4f4f4;
}

h1, h2, h3, h4, h5 {
  font-family: 'Roboto Slab', serif;
  font-weight: lighter;
}

#contacts h5 {font-size: 4em; color: #191970}

#form_input {
  margin-top: 25px;
  font-size: 1.1em;
}

@media (min-width: 1051px) {
  #form_input {
    width: 35%;
    margin-left: 38%;
  }
}


#form_input label {
  color: #505050;
  cursor: pointer;
  font-size: 1.4em;
  font-family: 'Roboto Slab', serif;
}

#form_input label > span {
  color: #e87e7e;
}

#form_input input,#form_input textarea {
  margin-bottom: 10px;
  width: 70%;
  padding: 10px 2%;
  border-radius: 10px;
  border: 2px solid silver;
  font-size: 0.9em;
  color: #4a4a4a;
}

#form_input input:focus, #form_input textarea:focus {
  border-color: #333;
}

.btn {
  float: left;
  border-radius: 7px;
  padding: 7px 9px;
  font-size: 1.2em;
  background-color: #00BFFF;
  text-shadow: #454545 0 0 2px;
  cursor: pointer;
  color: white;
  font-family: 'fantasy', serif;
}

.btn:hover {
  background-color: #0000FF;
}


