Что надо сделать:
1) Создайте index.html и подключите к нему файл scripts.js
2) Создайте переменную, в нее поместите текст Hello World
3) Выведите содержимое переменной во всплывающем сообщении(alert)
4) Создайте переменную с типом boolean и number.
5) Сложите boolean и number переменные и выведите результат в консоль разработчика с помощью console.log().
Напешите в комментарии, почему результат вышел именно таким.
6) Перепишите 'if..else' в '?'
let message, login = """";

if (login == 'Сотрудник') {
  message = 'Привет';
} else if (login == 'Директор') {
  message = 'Здравствуйте';
} else if (login == '') {
  message = 'Нет логина';
} else {
  message = '';
}

7) Напишите условие if для проверки, что переменная age находится в диапазоне между 18 и 80 включительно.
«Включительно» означает, что значение переменной age может быть равно 18 или 80.

8) При помощи цикла for выведите с помощью console.log нечётные числа от 1 до 9. Затем сделайте то же самое с помощью while.
9) Напишите функцию max(a,b), которая возвращает большее из чисел a и b.