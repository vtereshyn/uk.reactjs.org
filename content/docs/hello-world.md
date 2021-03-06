---
id: hello-world
title: Hello World
permalink: docs/hello-world.html
prev: cdn-links.html
next: introducing-jsx.html
---

The smallest React example looks like this:
Найменший приклад React виглядає наступним чином:

```js
ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
```

На сторінці з'явиться заголовок "Hello, world!"

[](codepen://hello-world)

Натисніть на посилання вище, щоб відкрити онлайн-редактор. Спробуйте відредагувати код і подивіться, як зміниться результат. Більшість сторінок цього посібника матимуть такі інтерактивні приклади.


## Як читати цей посібник {#how-to-read-this-guide}

У цьому посібнику ми розглянемо будівельні блоки React-додатків: елементів і компонентів. Засвоївши їх, ви зможете створювати складні додатки з невеликих повторно використовуваних частин.

>Порада
>
>Цей посібник призначений для людей, які віддають перевагу **вивченню базових понять крок за кроком**. Якщо ви віддаєте перевагу вчитися на практиці, ознайомтеся з нашим [практичним навчальним посібником](/tutorial/tutorial.html). Практичний навчальний підручник і цей посібник чимось доповнюють один одного.

Це перший розділ покрокового посібника про основні поняття React. Ви можете знайти перелік усіх його розділів на боковій панелі навігації. Якщо ви читаєте посібник з мобільного пристрою, відкрити навігаційне меню можна натиснувши кнопку в правому нижньому кутку екрану.

Кожен розділ у цьому посібнику базується на знаннях з попередніх розділів. **Більшу частину React можна вивчити, прочитавши розділи посібника «Основні поняття» в тому порядку, в якому вони перераховані на бічній панелі.** Наприклад, [“Вступ до JSX”](/docs/introducing-jsx.html) - наступний розділ.

## Необхідний рівень знань {#knowledge-level-assumptions}

React - це бібліотека JavaScript, тому ми припускаємо, що у вас є базове розуміння мови JavaScript. **Якщо ви відчуваєте себе не дуже впевнено, ми радимо [переглянути JavaScript посібник](https://developer.mozilla.org/uk/docs/Web/JavaScript/A_re-introduction_to_JavaScript), щоб перевірити свій рівень знань**; це полегшить читання посібника по React. Це може зайняти від 30 хвилин до години, але в результаті у вас не буде відчуття, що ви одночасно вивчаєте і React, і JavaScript.

>Примітка
>
>У прикладах посібника іноді використовуються новий синтаксис JavaScript. Якщо ви не працювали з JavaScript протягом останніх кількох років, [ці три пункти](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) допоможуть вам.


## Починаємо! {#lets-get-started}

Прокрутіть сторінку трохи нижче безпосередньо перед нижнім колонтитулом веб-сайту, щоб знайти посилання до [наступного розділу цього посібника](/docs/introducing-jsx.html).

