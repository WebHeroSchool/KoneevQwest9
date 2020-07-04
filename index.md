<!DOCTYPE html>
<html>
  <head>
   <title>
    Структурные теги
  </title>
</head>
 <body>
  <header> Шапка
     <nav>
       <a href='#'> Главная</a>
       <a href='#'> Подробнее</a>
       <a href='#'> Контакты</a>
    </nav>
  </header>
     <section>
    <p>
    Первая секция
    </p>
   </section>
   <section>
  <p>
     Вторая секция
   </p>
   </section>
   <section>
    <article>
      <p>
        Важная часть контента
      </p>
      <aside>
       <p>
       Контент который являетя второcтипенным, но связан с основным  контентом этого блока.
           </p>
        </aside>
        </article>
      </section>
     <footer>Подвал</footer>
     </body>
     </html>

     header {
  background: lightpink;
}

section {
  background: #c4c4c4;
}

article {
  border: dashed 1px #000;
}

aside {
  border: dashed 1px red;
}

footer {
  background: lightgreen;
}
