![image](https://github.com/user-attachments/assets/279b9b06-8cef-448f-a7dc-f1882e80c588)# Практическая работа №6.1 
# Создание автоматизированных Unit-тестов
## Выполнила: Никифорова Юлия 3ИСИП-422
### Описание проекта
Проект представляет собой консольное приложение на C#, которое моделирует банковский счет с методами Debit и Credit. Для тестирования этих методов был создан проект модульных тестов.
### Скриншот результата работы приложения:
![image](https://github.com/user-attachments/assets/c1b0b432-8914-4c14-b229-45f8ab12b1f3)
### Скриншот окна «Обозреватель тестов»:
![image](https://github.com/user-attachments/assets/1f909ec4-0e32-4dee-a074-b867d88d4002)
### Скриншот «Обозреватель решений»:
![Uploading image.png…]()
### Вывод о проведенном тестировании:
В ходе выполнения практической работы было проведено модульное тестирование класса BankAccount с использованием фреймворка MSTest в Visual Studio. Тестирование включало проверку методов Debit и Credit, которые отвечают за списание и зачисление средств на банковский счет. Тестирование подтвердило корректность работы методов Debit и Credit класса BankAccount. Все тесты были пройдены успешно, что свидетельствует о:
1. правильной обработке допустимых и недопустимых значений;
2. корректной работе исключений;
3. соответствии фактических результатов ожидаемым.
##### Причина успеха тестов с методом Debit: 
Логика метода Debit была исправлена (замена += на -=), а также добавлены проверки на валидность суммы и соответствующие исключения.
##### Причина успеха тестов с методом Credit: 
Метод Credit изначально содержал проверку на отрицательные значения и корректно увеличивал баланс.
