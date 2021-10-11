# 1. Travel through the Russia

2. It is another Yandex Praktikum project in which i'm trying to make site adaptive for different window sizes. Also I use brief with 4 extentions, but it is not so detalysed, such previous was.

__The HTML structure is not so difficult__
```html
<div class="place">
          <h2 class="place__title">Куршская коса</h2>

          <div class="place__website">
            <p class="place__url-heading">url</p>
            <a class="place__link" href="http://park-kosa.ru">park-kosa.ru</a>
          </div>
          <img src="images/place-kosa.jpg" alt="куршская коса" class="place__image">
          <p class="place__paragraph">
            <span class="place__paragraph-break">Здесь, посреди лесов и песчаных дюн, вы сможете увидеть два водных
              горизонта &#8212; спокойного Куршского залива с одной стороны и подёрнутого рябью волн Балтийского
              моря с другой. Уникальная природная зона на краю российского анклава.
            </span>
            На этом Калининградская область не заканчивается. Для путешественника и
            исследователя там же по соседству &#8212; самая западная точка России, Балтийская коса, &#8212; и немецкое
            наследие россыпи небольших приморских городов. Атмосфера здешних мест исключает суету, окуная в
            спокойствие природы и запах стального, прохладного моря.
          </p>
        </div>
```
__And all CSS styles are also imported, using BEM methdology__

```css
@import url(../vendor/normalize.css);
@import url(../vendor/fonts.css);
@import url(../blocks/body/body.css);
@import url(../blocks/page/page.css);
@import url(../blocks/header/header.css);
@import url(../blocks/header/__logo/header__logo.css);
@import url(../blocks/header/__lang-links/header__lang-links.css);
@import url(../blocks/header/__lang-link/header__lang-link.css);
```

**Figma**

Design was made on Figma

* [pages on Figma](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0)

3. You can use this project to inspect how you can make your page flexible. Using grids and flex-boxes makes them accurate and nice.

4. I still hope, that i will complete this task and someday i will recieve some JavaScript knowledges from my sweatheart teachers

* [My site link](https://stereojim.github.io/russian-travel/)