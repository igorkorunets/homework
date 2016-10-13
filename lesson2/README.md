Домашнее задание:

1-я часть

Добавить 1е и 2е домашние задания в репозиторий jelementary_finches/homework используя fork/pull request концепцию. Как это сделать, можно почитать по этой ссылке https://guides.github.com/activities/forking Операции clone, commit, push и прочие команды для работы с git рекомендую делать в git bash, а не GitHub for Desktop, как описанно в статье по ссылке.

2-я часть
* Переменные

  Создайте три переменных с типами `int`, `float` и `String` и присвойте им любые значения. Вывести из значения используя вызов ```System.out.println()```


* Создание и вызов метода класса (функции). Цикл for.
  * Создайте метод, который выводит строку `*****` и сделайте его вызов в методе main 5 раз
  * Перепишите вызов метода так, чтобы использовался цикл for. Результат должен быть одинаков с предыдущим - 5 строк `*****`


* Операторы ветвления If-else. Цикл while

  Напишите функцию определения високосного года. Используя цикл while сделайте вызов этой функции для периода 2001-2016гг.
  >
Год високосный, если делится на 4 без остатка.
Но если год делится на 100 без остатка - он не високосный.
При этом если год делится на 400 без остатка - он високосный.

* Цикл do-while. Выход из цикла break
  * Напишите бесконечный цикл do-while в котором сделайте вызов метода ```System.out.println("It seems that I'm here forever")```
  * Используя if и break сделайте выход из цикла. Условие выхода из цикла на ваше усмотрение. Например - вывод строки 5 раз.


3-я часть (необязательная)
  * Напишите метод, который конвертирует строку, содержащую целое число в двоичной системе счисления, в целое число в десятичной системе счисления.
  ```java
    public static int convert(String binary) {
      // your code here
      return 0;
    }
  ```

  * Для решения задачи используйте [Positional Notation](http://www.wikihow.com/Convert-from-Binary-to-Decimal)
  * Для получения нужного символа (char) из строки используйте следующие методы класса String: `charAt` и `length`    
    * http://docs.oracle.com/javase/7/docs/api/java/lang/String.html#charAt(int)
    * http://docs.oracle.com/javase/7/docs/api/java/lang/String.html#length()