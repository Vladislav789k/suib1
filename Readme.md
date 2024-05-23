# Этапы работы
1. Создал репозиторий на GitHub
![image](https://github.com/Vladislav789k/suib1/assets/71137501/a2e1f84b-bcba-4ae9-919a-99b5b149aa17)


2. Создал репозиторий на локальном Git

![image](https://github.com/Vladislav789k/suib1/assets/71137501/8da6a21a-ac4b-4ca3-be88-2d8fc5d34642)


3. Перешол в репозиторий

![image](https://github.com/Vladislav789k/suib1/assets/71137501/ec83ec3c-68ed-4d51-974a-e2b6486a1fd8)


4. Добавил в репозиторий файлы

![image](https://github.com/Vladislav789k/suib1/assets/71137501/f96565f8-f171-49f3-b834-13ea950a3244)


5. Создал первоначальную фиксацию пустого проекта, Создал ветку dev и переключился на неё и обратно

![image](https://github.com/Vladislav789k/suib1/assets/71137501/b29713ba-efed-4438-a129-1c70e38f45d5)

6. Объединил две ветки и назначил версию

![image](https://github.com/Vladislav789k/suib1/assets/71137501/e9e6a4f2-7455-43cf-9edf-a694fc5c3948)


7. Запушил на GitHub с локального Git

![image](https://github.com/Vladislav789k/suib1/assets/71137501/b81bba8f-4a78-407c-8a7d-bf6ce990ccf2)


# Описание кода 
Код включает в себя реализацию рекурсивной функции для вычисления степени числа и пример её использования. Код представлен ниже:
```
# -*- coding: utf-8 -*-
"""main.ipynb

Automatically generated by Colab.

Original file is located at
    https://colab.research.google.com/drive/1Ye1HD8XDW02CQ5T129hJC3X17LuXnnL9
"""

def power(a, n):
    # Базовый случай: если степень равна 0, результат всегда 1
    if n == 0:
        return 1
    # Рекурсивный случай: a^n = a * a^(n-1)
    return a * power(a, n - 1)

# Пример использования функции
a = 2.5
n = 3
result = power(a, n)
print(f"{a} в степени {n} равно {result}")
```
