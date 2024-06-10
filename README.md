
<h1 align="center">Привет, я Алексей
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h2 align="center">Начинающий тестировщик</h2>

<h3>
    Прошёл обучение в Skillbox и изучил основные методы тестирования
</h3>
<p>
    Тестировал онлайн 
<a href="https://intershop4.skillbox.ru" target=blank>
    магазин,
</a> 
    все найденный баги записывал в 
<a href=https://harrison4.youtrack.cloud/agiles/159-3/current target=blank>
    YouTrack
</a>
</p>
<h3>
    Цель проекта: онлайн-магазин для покупки товара. Пользователь может авторизоваться на сайте, просматривать товары добавлять в корзину и приобрести товар.
</h3>
<h4>
    Сайт состоит из нескольких частей:
</h4>
<ol>
    <li>
        Формы авторизации, регистрации и востановление пароля.
    </li>
    <li>
        Личный кабинет с данными пользователя и информацией по заказам.
    </li>
    <li>
        Главная - с нее осуществляются переходы вглубь сайта.
    </li>
    <li>
        Каталог товаров - раздел сайта, содержащий информацию о товарах или услугах.
    </li>
    <li>
        Карточка товара со всей информацией по товару в том числе отзывы пользователей.
    </li>
    <li>
        Корзина где пользователь может - проверить заказ и оформить покупку, узнать общую стоимость заказа, отказаться от некоторых выбранных товаров.
    </li>
    <li>
        Оформление заказа - финальная стадия работы с заказом. Место, где пользователь проверяет свой заказ, вводит адрес, оставляет комментарии и переходит к оплате.
    </li>
    <li>
        Оплата - в тестовом режиме, проходит мгновенно.
    </li>
 </ol>

<h4>
    Основной моей задачей было проверить онлайн-магазин на баги и ошибки и составить баг-репорты.
</h4>
<ul>
    <li>
        Первый мой шаг был проанализировать черновик аналитики для интернет магазина, найти баги, составить баг-репорты. В итоге нашёл
            <a href=https://harrison4.youtrack.cloud/issue/DP-1 target=blank>
                18 багов.
            </a> 
        В основном это были баги, которые противоречили логике проекта.
    </li>
<li>
    Далее ошибки аналитики были исправлены и я приступил к тестированию форм регистрации и авторизации. Нашёл
        <a href=https://https://harrison4.youtrack.cloud/issue/DP-23 target=blank>
            13 багов.
        </a>
    При тестировании формы регистрации, при помощи граничных значений, в поле Имя обнаружил
            <a href=https://harrison4.youtrack.cloud/issue/DP-30/Pri-registracii-pole-Imya-prinimaet-znachenie-menshe-5-simvolov. target=blank>
                баг
            </a> 
    связанный с минимальным количеством символов в поле.
</li>
<li>
    Для более точного и подробного составления тест-кейсов я сделал 
        <a href=https://harrison4.youtrack.cloud/issue/DP-36 target=blank>
            диаграмму 
        </a>
    переходов и состояний объекта товар.
</li>
<li>
    Для проверки общей работоспособности и функциональности сайта составил 
        <a href=https://docs.google.com/spreadsheets/d/1HY8yyX0VO7ZSIdf_LiUVVc8ZqY7UVCN2y6qOXXB8JnA/edit#gid=0 target=blank>
            тестовые сценарии.
        </a>
    Так-же тестовые сценарии помогли провести примерную оценку трудозатрат (80мин).
</li>
<li>
    Далее при помощи Postman тестировал API и нашёл 
        <a href=https://harrison4.youtrack.cloud/issue/DP-38 target=blank>
            7 багов на бэкенде
        </a> 
    связанных с разными методами. И 2 бага на фронте.
</li>
<li>
    При тестировании безопасности обнаружил 
        <a href=https://harrison4.youtrack.cloud/issue/DP-49/Na-sajte-mozhno-prosmatrivat-chuzhie-zakazy target=blank>
            IDOR-уязвимость
        </a>
    связанную с личными данными пользователей.
</li>
<li>
    После редизайна сайта проверил пользовательский интерфейс на соответствие с макетом из Figma и обнаружил 
        <a href=https://harrison4.youtrack.cloud/issue/DP-54 target=blank>
            16 багов.
        </a>
</li>
<li>
    Так-же после редизайна сайта провёл регресс-тестирование и обнаружил 
        <a href=https://harrison4.youtrack.cloud/issue/DP-74 target=blank>
            12 багов.
        </a>
    В этом мне помогли ранее составленные тестовые сценарии, заодно провёл оценку трудозатрат (90мин).
</li>
<li>
    В конце составил 
    <a href=https://docs.google.com/spreadsheets/d/12Yn8BkldNqcGGGRXNXC_oBqJREEsjcyBWQuSvBL5ptk/edit#gid=0 target=blank>
         сценарии для приёмочного тестирования.
    </a>
    В основном эти проверки затрагивают основной функционал сайта.
</li>
</ul>


Языки и инструменты

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)

📫 Как со мной связаться

📞 89055424532

📧 harison196@mail.ru

<!-- ![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white) -->

<!-- - 👋 Hi, I’m @AlexeyLitovskii
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ... -->

<!---
AlexeyLitovskii/AlexeyLitovskii is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
