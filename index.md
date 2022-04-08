<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.menu {
  float: left;
  width: 20%;
}
.menuitem {
  padding: 8px;
  margin-top: 7px;
  border-bottom: 1px solid #D3D3D3;
}
.main {
  float: left;
  width: 60%;
  padding: 0 20px;
  overflow: hidden;
}
.right {
  background-color: LightGrey;
  float: right;
  width: 20%;
  padding: 10px 15px;
  margin-top: 7px;
}

@media only screen and (max-width:800px) {
  /* For tablets: */
  .main {
    width: 80%;
    padding: 0;
  }
  .right {
    width: 100%;
  }
}
@media only screen and (max-width:500px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}

a {
  color: DarkSalmon; /* Цвет обычной ссылки */
  text-decoration: none; /* Убираем подчеркивание */
  padding: 2px; /* Поля вокруг текста */
  }
   a:visited {
    color: #800080; /* Цвет посещенной ссылки */
    text-decoration: none; /* Убираем подчеркивание */
   } 
   a:hover {
    text-decoration: none; /* Убираем подчеркивание */
    color: #2F4F4F; /* Цвет ссылки при наведении на нее курсора мыши */  
    background: #8FBC8F; /* Цвет фона */
   }
     table {
      background: #778899; /* Цвет фона таблицы */
      color: white; /* Цвет текста */
      width:100%
     }

  </style>
</head>
<body style="font-family:Verdana;color:Brown">

<div style="background-color:#FAEBD7;padding:15px;">
  <h1>С 8 марта</h1>
  <h3>С международным женским днем</h3>
</div>

<div style="overflow:auto">
  <div class="menu"> 
    <p><a href="rome.html">Список сотрудников</a></p>
    <p><a href="rome.html">Адрес эл. почты</a></p>
    <p><a href="rome.html">Телефон</a></p>
    <p><a href="rome.html">Календарь событий</a></p>
  </div>

  <div class="main">
    <h2>Поздравляем!</h2>
    <p>Уважаемые коллеги, желаем замечательного настроения и много-много улыбок. Пусть работа дает желанные результаты, всё получается легко и без препятствий. Огромного женского счастья, невероятно сильной любви и нежности, внимания и заботливого участия. Будьте готовы к лучшему, оно обязательно произойдет! С праздником!

</p>
 <br><hr width:100% size="10" color="#BDB76B" /> <br><br><br>
    <img src="http://ru-sled.ru/wp-content/uploads/2018/02/00-%D0%BB%D0%B8%D0%B4%D0%B8%D1%8F-%D0%BC%D1%83%D0%B7%D0%B0-%D0%BC%D0%B0%D1%82%D0%B8%D1%81%D1%81%D0%B0.jpg" style="width:100%">
    <p><i>Лидия Делекторская</i></p>
  </div>
 
  <div table="main" >
    <table>
    <tr>
    <th>Имена сотрудников</th>
    <th>Почта</th>
    </tr>
    <tr>
    <td>Олег</td>
    <td><p><a href="mailto:someone@example.com">Отправить письмо</a></p>
</td>
    </tr>
    <tr>
    <td>Илья</td>
    <td><p><a href="mailto:someone@example.com">Отправить письмо</a></p></td>
    </tr>
    <tr>
    <td>Михаил</td>
    <td><p><a href="mailto:someone@example.com">Отправить письмо</a></p></td>
    <tr>
    <td>Анастасия</td>
    <td><p><a href="mailto:someone@example.com">Отправить письмо</a></p></td>
    </tr>
  </table>
</div>

</body>
</html>

