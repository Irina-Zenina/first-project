# Научиться учиться #

Проект создан как практическая работа для "Яндекс Практикум" ипредставляет собой сайт, рассказывающий о том,  
как правильно проходить обучения и какие хитрости можно использовать. 
Здесь вы узнаете о:
1. Техниках обучения.
2. Принципах обучения.
3. Что за "зверь" такой "прокрастинация" и как его победить?
4. Интересных фактах и цифрах об учебе и человеческом мозге.
5. Полезных ресурсах и книгах.

В рамках проекта была подготовлена html-верстка страницы и ее стили, основанные на БЭМ методологии. Особое внимание уделялось flex-контейнерам и их позиционированию.
Также в рамках проекта была реализована анимация для некоторых элементов:
```
@keyframes rotation {
  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }
}

.rotation {
  animation: rotation running 20s ease-in infinite;
}
```
В дальнейшем хотелось бы также использовать JavaScript для расширения возможностей сайта, а также разработать страницы разделов "Метод Феймана",
"Концепция", "Наставники", добавить ссылки на социальные сети и интернет-магазин, где можно купить книгу Салмана Хана "Весь мир - школа".
