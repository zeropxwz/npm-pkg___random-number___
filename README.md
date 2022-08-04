# random number

## описание

Функция генерирует и возвращает случайное число в заданном диапазоне.  
Имеет два обязательныъ параметра и один опциональный

### сигнатура функции
```ts
function randomNumber(
    begin: number, 
    end: number, 
    type?: 'int' | 'float'        
)
: number | void
```

### использование
параметры задают границы диапазона: 1й - начало, 2й - конец  
```ts
console.log(
    randomNumber(0, 10) // выведет число в диапазоне от 0 до 10
)
```
чтобы получить число с плавающей точкой или явно задать целочисленный возвращающий тип используется праметр type со значением 'int' или 'float'  
```ts
console.log(
    randomNumber(0, 10, 'float') // выведет число в диапазоне от 0 до 10 с плавающей точкой
)
```
