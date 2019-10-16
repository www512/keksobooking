# Личный проект «Кексобукинг»

**Сайт:** https://www512.github.io/keksobooking/


## О проекте
Кексобукинг — сервис размещения объявлений о сдаче в аренду недвижимости в центре Токио. Пользователям предоставляется возможность размещать объявления о своей недвижимости или просматривать уже размещённые объявления.


- При первом открытии, страница находится в неактивном состоянии: блок с картой находится в неактивном состоянии, форма подачи заявления заблокирована. Единственное доступное действие в неактивном состоянии — перетаскивание метки, являющейся контролом указания адреса объявления. Первое перемещение метки переводит страницу в активное состояние.
- В активном состоянии страница позволяет вносить изменения в форму и отправлять её на сервер, просматривать похожие объявления на карте, фильтровать их и уточнять подробную информацию о них, показывая для каждого из объявлений карточку.
- Заполнение всей информации производится на одной странице без промежуточных переходов. Порядок заполнения информации не важен. После заполнения всех данных, при нажатии на кнопку «Опубликовать», все данные из формы, включая изображения, с помощью AJAX-запроса отправляются на сервер.
- При успешной отправке формы страница, не перезагружаясь, переходит в изначальное неактивное состояние.
- Если при отправке данных произошла ошибка запроса, показывается соответствующее сообщение.
- Нажатие на кнопку «Очистить» сбрасывает страницу в исходное неактивное состояние без перезагрузки.

[Техническое задание](https://up.htmlacademy.ru/javascript/17/project/keksobooking)

---
<a href="https://htmlacademy.ru"><img align="left" width="50" height="50" alt="HTML Academy" src="https://up.htmlacademy.ru/static/img/intensive/htmlcss/logo-for-github.svg"></a>

Проект разработан в рамках интенсивного курса «[Профессиональный онлайн‑курс JavaScript, уровень 1](https://htmlacademy.ru/intensive/javascript)» от [HTML Academy](https://htmlacademy.ru).