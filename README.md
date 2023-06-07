# Страница интернет-магазина

Учебный проект курса [React для JS-разработчиков](https://netology.ru/programs/react)

## **Задача**

Создание React-компонента ShopItemFunc (функциональный компонент), с помощью которого возможно реализовывать представление информации о товарах из каталога на сайте в таком виде (компонент обведён пунктирной линией):

![preview](./public/images/preview.png)

## **Описание компонента**

Компонент должен иметь один props `item`, в котором он ожидает объект с информацией о товаре со следующими свойствами:

- `brand` — название производителя товара;
- `title` — название товара;
- `description` — краткое описание товара;
- `descriptionFull` — подробное описание товара;
- `price` — цена товара;
- `currency` — валюта товара.

Компонент должен создавать DOM элемент следующей структуры:

```JavaScript
<div class="main-content">
  <h2>Tiger of Sweden</h2>
  <h1>Leonard coat</h1>
  <h3>Minimalistic coat in cotton-blend</h3>
  <div class="description">
    Men's minimalistic overcoat in cotton-blend. Features a stand-up collar, concealed front closure and single back vent. Slim fit with clean, straight shape. Above-knee length.
  </div>
  <div class="highlight-window mobile"><div class="highlight-overlay"></div></div>
  <div class="divider"></div>
  <div class="purchase-info">
    <div class="price">£399.00</div>
    <button>Добавить в корзину</button>
  </div>
</div>
```
## **Стек технологий**
<img src="https://img.shields.io/badge/HTML-161130?style=for-the-badge&logo=html5&logoColor=ЦВЕТ ЛОГОТИПА"/>
<img src="https://img.shields.io/badge/CSS-161130?style=for-the-badge&logo=css3&logoColor=0091d5"/>
<img src="https://img.shields.io/badge/JavaScript-161130?style=for-the-badge&logo=javascript&logoColor=efd81d"/>
<img src="https://img.shields.io/badge/GIT-161130?style=for-the-badge&logo=git&logoColor=E84E31"/>
<img src="https://img.shields.io/badge/REACT-161130?style=for-the-badge&logo=react&logoColor=ЦВЕТ ЛОГОТИПА"/>

## [**Демо**](https://store-func.vercel.app/)
![demo](./public/images/demo.jpg)
