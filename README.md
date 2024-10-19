
# Лабораторная работа №2. Основы верстки
- _Выполнила:_ Плотникова Вероника
- _Язык программирования:_ Java

## Что делает приложение?
Приложение состоит из 4 экранов:
1. [Меню](#activity1).
2. [Экран 2](#activity2), который сверстан с использованием `LinearLayout`.
3. [Экран 3](#activity3), который сверстан с использованием `RelativeLayout`.
4. [Экран 4](#activity4).

<p align="center">
    <img src="https://github.com/user-attachments/assets/461d63d8-0afa-44f6-b38d-095549ea34dc" width="200"> 
    <img src="https://github.com/user-attachments/assets/39384a63-f736-4fe1-a339-c85f2c3fa976" width="200">
    <img src="https://github.com/user-attachments/assets/2f8970d5-bdad-40bd-9d4f-abfdbeec8069" width="200"> 
    <img src="https://github.com/user-attachments/assets/805b2c82-c7ed-4a65-ba4f-2ff94b8b8594" width="200">
</p> 
Возврат на предыдущий экран осуществляется при помощи системной кнопки / бэксвайпа

---
### <a id="activity1"> Меню (экран 1) </a>

**_Меню состоит из 4х кнопок:_**
- **"Экран 2"**. - > открытие [`SecondActivity`](#activity2)
- **"Экран 3"**. -> открытие [`ThirdActivity`](#activity3)
- **"Экран 4"**. -> открытие [`FourthActivity`](#activity4)
- **"Выйти"**. -> выход из приложения.

_**Характеристики кнопок:**_
- высота каждой кнопки составляет **20%** от высоты экрана
- расстояние между кнопками - **2%**
- ширина кнопок - **75%**
- расстояние от первой кнопки до верхнего края **==** расстоянию от последней кнопки до нижнего края **== 7%**
- кнопки выровнены по центру.
  <p align="center">
    <img src="https://github.com/user-attachments/assets/461d63d8-0afa-44f6-b38d-095549ea34dc" width="200"> 
</p> 

---
### <a id="activity2"> Экран 2 (SecondActivity)</a>
**Особенность экрана:** сверстан с использованием `LinearLayout`.

**Состоит из 7 кнопок:**
- 3 расположены в верхней части экрана и занимают равную ширину
- 2 расположены по центру, занимают равные части, но имеют отступы от краев
- 3 расположены в нижней части экрана:
  - 1 занимает половину всей ширины экрана
  - 2 делят оставшуюся часть поровну между собой
  <p align="center">
    <img src="https://github.com/user-attachments/assets/39384a63-f736-4fe1-a339-c85f2c3fa976" width="200">
</p> 

---

### <a id="activity3"> Экран 3 (ThirdActivity)</a>
**_Особенность экрана:_** сверстан с использованием `RelativeLayout`, т.е. местоположение объектов задается относительно других.

**Состоит из 6 кнопок:**
- 2 расположены в верхней части экрана и занимают по половине экрана
- 3 расположены по центру
- 1 расположена в нижней части экрана

<p align="center">
    <img src="https://github.com/user-attachments/assets/2f8970d5-bdad-40bd-9d4f-abfdbeec8069" width="200"> 
</p> 

 ---
### <a id="activity4"> Экран 4 (FourthActivity)</a>

На экране расположена всего 1 кнопка. Ее особенности:
- выровнена по центру экрана
- имеет темно-зеленый цвет
- слева от текста изображена иконка приложения
- цвет обводки кнопки `#505050`
- толщина обводки `7px` (т.к. я родилась в июле)
- радиус скругления кнопки `24dp`
- при нажатии на кнопку ее цвет изменяется на светло-зеленый.
<p align="center">
    <img src="https://github.com/user-attachments/assets/805b2c82-c7ed-4a65-ba4f-2ff94b8b8594" width="200">
    <img src="https://github.com/user-attachments/assets/e2a0bdd8-fcb0-4c04-a111-5b396ec15dd2" width="200"> 
</p> 
