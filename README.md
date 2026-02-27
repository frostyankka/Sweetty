<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Сладость</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="styles/normalize.css">
</head>
<body>
    

    <section class="banner first">
        <div class="content">
            <h1>БОЖЕСТВЕННАЯ КОНДИТЕРСКАЯ</h1>
            <h2>СДЕЛАНО С ЛЮБОВЬЮ</h2>
        </div>
    </section>

    <!-- Шапка сайта с логотипом и панелью навигации -->

   <header>

    

    <nav>
        <a href="index.html">
        <div class="logo"><img id="logo" src="img\logo.jpeg" alt="Лого"></div>
        </a>
        <ul>
        <li><a href="cakes.html">Готовые торты</a></li>
        <li><a href="filling.html">Начинка</a></li>
        <li><a href="delivery.html">Доставка</a></li>
        <li><a href="index.html#feedback">Контакты</a></li>
    </nav>

   </header>

   <!-- Секция для рекламного баннера -->

    <section class="banner">

    <div class="content">   </div>

    </section>

    <!-- Секция Наши преимущества -->

    <section class="advantages">

        <div class="content">

            <div class="advantage">
                <img src="img\icons\icon-1.png":width="60px" height="60px" alt="Натуральные продукты">
                <p>Только<br > натуральные продукты</p>
            </div>

            <div class="advantage">
                <img src="img\icons\icon-2.png":width="60px" height="60px" alt="Натуральные продукты">
                <p>Без консервантов,<br > срок хранения 48 часов</p>
            </div>

            <div class="advantage">
                <img src="img\icons\icon-3.png":width="60px" height="60px" alt="Индивидуальный дизайн">
                <p>Индивидуальный дизайн</p>
            </div>

            <div class="advantage">
                <img src="img\icons\icon-4.png":width="60px" height="60px" alt="Разнообразие вкусов">
                <p>Разнообразие<br > вкусов в одном торте</p>
            </div>

        </div>

    </section>

    <!-- Секция для выбора услуги -->

    <section class="select">

        <div class="content">

            <div class="select_cakes">

                <img id="cake1" src="img\select-cake-1.jpg":width="450px" height="300px" alt="Выбрать готовый торт">
                <a href="cakes.html">ВЫБРАТЬ ГОТОВЫЙ</a>

            </div>

            <div class="select_cakes">

                <img id="cake2" src="img\select-cake-2.jpg":width="450px" height="300px" alt="Выбрать готовый торт">
                <a href="cakes.html">ЗАКАЗАТЬ СВОЙ</a>

            </div>

        </div>

    </section>

    <!-- Секция для блока О компании -->

    <section class="about">

        <div class="about_wrap">

            <div class="about_text">
                <p>Меня зовут Карина - я профессиональный кондитер и хозяйка Моей Сладости.</p>
                <p>Мой девиз - честная и открытая работа, индивидуальный подход.</p>
                <p>В моих тортиках только натуральные ингридиенты и качественные продукты.</p>
            </div>

        </div>

    </section>

    <!-- Секция для отзывов клиентов-->


    <section class="reviews">

        <div class="content">


            <div class="review">
                
                

                <div class="review_text">
                    <img id="review1" src="img\reviews\review-1.jpg":width="300px" height="300px" alt="Покупатель">
                <blockquote>
                1. Внимательное отношение к клиенту, вкуснющий торт и некусачие цены! Огромное спасибо за удовольствие! Екатерине творческих успехов!
                </blockquote>

                <img id="review2" src="img\reviews\review-2.jpg":width="300px" height="300px" alt="Покупатель">

                <div class="review_text">

                <blockquote>
                2. Торт натуральный, выполнен искусно, и подложка лишь подчеркнула торжественное лакомство! Спасибо и успехов вашему бизнесу!
                </blockquote>

                <img id="review3" src="img\reviews\review-3.jpg":width="300px" height="300px" alt="Покупатель">

                <div class="review_text">

                <blockquote>
                3. Изысканный вкус тортиков не оставил равнодушным ни одного сотрудника нашего Холдинга! Огромное спасибо за настроение, сладкую жизнь и превосходный вкус и дизайн Ваших тортов!
                </blockquote>

                </div>

            </div>


        </div>

    </section>

    <!-- Секция для блока обратной связи с клиентом -->

    <section class="feedback">

        <div class="content">

            <form action="answer.html">

            <div class="form_contact">
                <input placeholder="Введите имя" type="text" pattern="[а-яА-ЯёЁ]{2,15}" required title="например, Александр">
                <input placeholder="Введите номер телефона" required type="tel" name="tel-number" id="tel-number" title=" например, 89123456789"  pattern="8[0-9]{3}[0-9]{3}[0-9]{2}[0-9]{2}">
            </div>

            <div class="form_download">
                <br>ЕСТЬ ФОТО ПРИМЕРА?
                <label for="download"><br>ЗАГРУЖАЙ ЗДЕСЬ</label>
                <input type="file" id="download" name="download" accept=".png, .jpg, .jpeg">
            </div>

            <div class="form_submit">
                <div class="form__submit">
                <input type="checkbox" name="personal" id="personal" required>
                <label for="personal">
                Я СОГЛАСЕН НА ОБРАБОТКУ ПЕРСОНАЛЬНЫХ ДАННЫХ
                </label>
                </div>
                <input type="submit" value="ПООБЩАТЬСЯ">
                </div>

                </form>

        </div>

    </section>

    <!-- Секция для блока с картой -->

    <section class="map">

        <div class="content">
            <h2>МЫ НА КАРТЕ</h2>
            <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2689.29088229398!2d16.869265976994555!3d47.62047667119105!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x476c1aaf59ab8731%3A0x8ed9d5897abe4753!2z0K3RgdGC0LXRgNGF0LDQt9Cw!5e0!3m2!1sru!2sru!4v1768800857646!5m2!1sru!2sru"
                style="border: 0"
                allowfullscreen=""
                loading="lazy"
            ></iframe>
            <h2>Fertőd, Joseph Haydn u. 2, 9431 Венгрия</h2>
        </div>

    </section>

    <!-- Подвал сайта с контактной информацией -->

    <footer>

        <div class="content">


            <div class="footer_main">

                <div class="footer_info">Домашняя кондитерская<br>"Моя сладость"<br>ИП Иванова Е.И.<br>Все права защищены</div>

                <div class="footer_social">
                    <h2>Мы в социальных сетях</h2>
                    <a href="http://vk.com"><img src="img\icons\icon-5.png":width="30px" height="30px" alt="Вконтакте"></a>
                    <a href="http://instagram.com" ><img src="img\icons\icon-6.png":width="30px" height="30px" alt="Инстаграм"></a>
                </div>

                <div class="footer_menu">

                    <nav>
                        <ul>
                        <li><a href="cakes.html">Готовые торты</a></li>
                        <li><a href="filling.html">Начинка</a></li>
                        <li><a href="delivery.html">Доставка</a></li>
                        <li><a href="index.html#feedback">Контакты</a></li>
                    </ul>
                </nav>

                </div>

            </div>

            <div class="footer_add">При создании учебного сайта использовались изображения с портала:<br><a href="http://pixabay.com/ru/">pixabay.com</a><br>Источники вдохновения и текстового содержимого:<br><a href="http://master-chocolate.ru/">master-chocolate.ru</a> и <a href="http://www.sorokatort.ru/">www.sorokatort.ru</a>
            </div>

        </div>

    </footer>

</body>
</html>
