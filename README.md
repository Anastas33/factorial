# factorial

// функция для вычисления факториала числа

function factorial(n) {
    if (n === 0 || n === 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}

// Пример использования:
let number = 5;
let result = factorial(number);
console.log(`Факториал числа ${number} равен ${result}`);
```

Этот код определяет функцию `factorial`, которая вычисляет факториал числа `n`.
