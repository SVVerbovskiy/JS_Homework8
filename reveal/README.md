# Появление элементов при прокрутке

Домашнее задание к занятию 2.1 «DOM».

## Описание 

Необходимо реализовать механизм появления блоков в тот момент, когда прокрутка 
дойдёт до них

![Demo](./demo.gif)

### Исходные данные

1. Основная HTML-разметка
2. Базовая CSS-разметка

Разметка элементов выглядит следующим образом:

```html
<div class="reveal">
    <!-- содержимое блока -->
</div>
```

Отображение блока осуществляется путём присовения класса *reveal_active*:

```html
<div class="reveal reveal_active">
    <!-- содержимое блока -->
</div>
```
