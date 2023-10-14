Here you can see all my homeworks that were done during the courses of Vadim Ksendzov "Software testing course" and Artsiom Rusau - "Functional testing of Software"

# **Software testing course by Vadim Ksendzov**

In the absence of formal documentation for testing, the testing of API were based on the guidance and instructions provided by the owner of the course.

## Homework-1
[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/20918959-4a1fd678-4ee0-408f-a36a-6f6c91014abf?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D20918959-4a1fd678-4ee0-408f-a36a-6f6c91014abf%26entityType%3Dcollection%26workspaceId%3Dca964f13-848f-4b00-8ba2-f7031801ec6b)

## Homework-2
[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/20918959-5c5dc0d2-bd6b-4f7a-90c7-7c515ae79563?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D20918959-5c5dc0d2-bd6b-4f7a-90c7-7c515ae79563%26entityType%3Dcollection%26workspaceId%3Dca964f13-848f-4b00-8ba2-f7031801ec6b)

## Homework-3
[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/20918959-4a1a2b9b-bd0b-49f4-badb-c56fc3d5fdaf?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D20918959-4a1a2b9b-bd0b-49f4-badb-c56fc3d5fdaf%26entityType%3Dcollection%26workspaceId%3Dca964f13-848f-4b00-8ba2-f7031801ec6b)

# **Functional testing of Software course by Artsiom Rusau**

The documentation utilized for the functional testing of software was sourced from the official documentation provided by the Swagger Petstore API, available at _https://petstore.swagger.io/._

## Homework-1 Petstore
[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/20918959-d60d0309-6b37-407f-a7f4-4e1d383a2ac9?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D20918959-d60d0309-6b37-407f-a7f4-4e1d383a2ac9%26entityType%3Dcollection%26workspaceId%3D64867cde-bf6d-4a68-999f-d539fe76bc17)

## Homework-2 WSDL
[![Run in Postman](https://run.pstmn.io/button.svg)](https://god.gw.postman.com/run-collection/20918959-3fe82d20-364f-4e19-92ef-b71be1dc82c5?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D20918959-3fe82d20-364f-4e19-92ef-b71be1dc82c5%26entityType%3Dcollection%26workspaceId%3D64867cde-bf6d-4a68-999f-d539fe76bc17)

------------------
<details>
<summary>
  Homework description 
</summary>

## **Homework-1**
Create requests in Postman
* Protocol: http
* IP: 162.55.220.72
* Port: 5005

### Task 1
Method: GET\
EndPoint: /get_method\
request url params: 
* name: str
* age: int

response: \
[\
    “Str”,\
    “Str”\
    ]

==================

### Task 2
Method: POST\
EndPoint: /user_info_3\
request form data:
* name: str
* age: int
* salary: int

response: \
{'name': name,\
'age': age,\
'salary': salary,\
'family': {'children': [['Alex', 24], ['Kate', 12]],\
&emsp;&emsp;&emsp;'u_salary_1_5_year': salary * 4}}

==================

### Task 3
Method: GET\
EndPoint: /object_info_1\
request url params: 
* name: str
* age: int
* weight: int

response:\
{'name': name,\
'age': age,\
'daily_food': weight * 0.012,\
'daily_sleep': weight * 2.5\
}

==================

### Task 4
Method: GET
EndPoint: /object_info_2
request url params: 
* name: str
* age: int
* salary: int

response: \
{'start_qa_salary': salary,\
'qa_salary_after_6_months': salary * 2,\
'qa_salary_after_12_months': salary * 2.7,\
'qa_salary_after_1.5_year': salary * 3.3,\
'qa_salary_after_3.5_years': salary * 3.8,\
'person': {'u_name': [user_name, salary, age],\
&emsp;&emsp;&emsp;'u_age': age,\
&emsp;&emsp;&emsp;'u_salary_5_years': salary * 4.2}\
}

==================

### Task 5
Method: GET
EndPoint: /object_info_3
request url params: 
* name: str
* age: int
* salary: int

response: \
{'name': name,\
'age': age,\
'salary': salary,\
'family': {'children': [['Alex', 24], ['Kate', 12]],\
&emsp;&emsp;&emsp;'pets': {'cat': {'name':'Sunny',\
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;'age': 3},\
&emsp;&emsp;&emsp;'dog': {'name':'Luky',\
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;'age': 4}},\
'u_salary_1_5_year': salary * 4}\
}

==================

### Task 6
Method: GET
EndPoint: /object_info_4
request url params: 
* name: str
* age: int
* salary: int

response: \
{'name': name,\
'age': int(age),\
'salary': [salary, str(salary * 2), str(salary * 3)]\
}

==================

### Task 7
Method: POST
EndPoint: /user_info_2
request form data: 
* name: str
* age: int
* salary: int

response: \
{'start_qa_salary': salary,\
'qa_salary_after_6_months': salary * 2,\
'qa_salary_after_12_months': salary * 2.7,\
'qa_salary_after_1.5_year': salary * 3.3,\
'qa_salary_after_3.5_years': salary * 3.8,\
'person': {'u_name': [user_name, salary, age],\
&emsp;&emsp;&emsp;
'u_age': age,\
&emsp;&emsp;&emsp;
'u_salary_5_years': salary * 4.2}\
}


## <b>Homework-2</b>
### Task 1
http://162.55.220.72:5005/first
1. Отправить запрос.
2. Статус код 200
3. Проверить, что в body приходит правильный string.

==================

### Task 2
http://162.55.220.72:5005/user_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Проверить, что name в ответе равно name s request (name вбить руками.)
5. Проверить, что age в ответе равно age s request (age вбить руками.)
6. Проверить, что salary в ответе равно salary s request (salary вбить руками.)
7. Спарсить request.
8. Проверить, что name в ответе равно name s request (name забрать из request.)
9. Проверить, что age в ответе равно age s request (age забрать из request.)
10. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
11. Вывести в консоль параметр family из response.
12. Проверить что u_salary_1_5_year в ответе равно salary*4 (salary забрать из request)

==================

### Task 3
http://162.55.220.72:5005/object_info_3
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age s request (age забрать из request.)
7. Проверить, что salary в ответе равно salary s request (salary забрать из request.)
8. Вывести в консоль параметр family из response.
9. Проверить, что у параметра dog есть параметры name.
10. Проверить, что у параметра dog есть параметры age.
11. Проверить, что параметр name имеет значение Luky.
12. Проверить, что параметр age имеет значение 4.
13. *Преобразовать задания 5-7 (сравнить идентичные поля в реквесте и респонсе) таким образом, чтобы это делалось ЗА ОДИН ТЕСТ (сразу все 3 поля) БЕЗ ЦИКЛОВ! (глубокое сравнение объектов)

==================

### Task 4
http://162.55.220.72:5005/object_info_4
1. Отправить запрос.
2. Статус код 200
3. Спарсить response body в json.
4. Спарсить request.
5. Проверить, что name в ответе равно name s request (name забрать из request.)
6. Проверить, что age в ответе равно age из request (age забрать из request.)
7. Вывести в консоль параметр salary из request.
8. Вывести в консоль параметр salary из response.
9. Вывести в консоль 0-й элемент параметра salary из response.
10. Вывести в консоль 1-й элемент параметра salary параметр salary из response.
11. Вывести в консоль 2-й элемент параметра salary параметр salary из response.
12. Проверить, что 0-й элемент параметра salary равен salary из request (salary забрать из request.)
13. Проверить, что 1-й элемент параметра salary равен salary*2 из request (salary забрать из request.)
14. Проверить, что 2-й элемент параметра salary равен salary*3 из request (salary забрать из request.)
15. Создать в окружении переменную name
16. Создать в окружении переменную age
17. Создать в окружении переменную salary
18. Передать в окружение переменную name
19. Передать в окружение переменную age
20. Передать в окружение переменную salary
21. Написать цикл который выведет в консоль по порядку элементы списка из параметра salary.

==================

### Task 5
http://162.55.220.72:5005/user_info_2
1. Вставить параметр salary из окружения в request
2. Вставить параметр age из окружения в age
3. Вставить параметр name из окружения в name
4. Отправить запрос.
5. Статус код 200
6. Спарсить response body в json.
7. Спарсить request.
8. Проверить, что json response имеет параметр start_qa_salary
9. Проверить, что json response имеет параметр qa_salary_after_6_months
10. Проверить, что json response имеет параметр qa_salary_after_12_months
11. Проверить, что json response имеет параметр qa_salary_after_1.5_year
12. Проверить, что json response имеет параметр qa_salary_after_3.5_years
13. Проверить, что json response имеет параметр person
14. Проверить, что параметр start_qa_salary равен salary из request (salary забрать из request.)
15. Проверить, что параметр qa_salary_after_6_months равен salary*2 из request (salary забрать из request.)
16. Проверить, что параметр qa_salary_after_12_months равен salary*2.7 из request (salary забрать из request.)
17. Проверить, что параметр qa_salary_after_1.5_year равен salary*3.3 из request (salary забрать из request.)
18. Проверить, что параметр qa_salary_after_3.5_years равен salary*3.8 из request (salary забрать из request.)
19. Проверить, что в параметре person, 1-й элемент из u_name равен salary из request (salary забрать из request.)
20. Проверить, что что параметр u_age равен age из request (age забрать из request.)
21. Проверить, что параметр u_salary_5_years равен salary*4.2 из request (salary забрать из request.)
22. *Написать цикл который выведет в консоль по порядку элементы списка из параметра person. будут проходить ОБА теста.
23. *Преобразовать задания 8 - 13 (проверить что в json имеется нужный параметр) таким образом, чтобы все проверки делались в цикле (1 проверка в цикле, в которую попадают нужные параметры). Название теста должно видоизменяться исходя из подаваемых данных. ( ${}  или другим способом)
24. *Преобразовать задания 14 - 18 (проверить что параметр равен salary умножить на коэффициент) таким образом, чтобы все проверки делались в цикле (1 проверка в цикле, в которую попадают нужные параметры). Название теста должно видоизменяться исходя из подаваемых данных. ( ${}  или другим способом)
25. *Преобразовать описанные выше задания 1 и 2 для данного эндпоинта в ОДИН ЦИКЛ, в котором будут проходить ОБА теста.


## <b>Homework-1 Petstore</b>
В рамках задания вам необходимо протестировать все методы, которые представлены для сервиса https://petstore.swagger.io/ в Postman и создать соответствующие коллекции.\
Обязательно используйте переменные для упрощения своей работы в Postman, например, для базового URL.\
Помимо создания коллекции по всем методам вам также вам необходимо:\
1. Написать тест, который проверяет статус код после удаления домашнего животного из базы
2. Создать несколько юзеров, используя метод createdWithArray
3. В теле запроса для создания питомца сделать динамические значения, которые будут автоматически генерироваться при отправке


## <b>Homework-2 WSDL</b>
Используя следующую WSDL https://is.gd/Tm9giG создайте рабочую коллекцию в Postman, с помощью которых можно определить: валюту страны, полную информацию о стране и информацию о языке конкретной страны. \
Для быстрой работы с методами установите расширение Wizdler для браузера.


</details>
