University: [ITMO University](https://itmo.ru/ru/)\
Faculty: [FTMI](https://ftmi.itmo.ru)\
Course: [Cloud platforms as the basis of technology entrepreneurship](https://itmo-ict-faculty.github.io/cloud-platforms-as-the-basis-of-technology-entrepreneurship/education/labs2023-2024/lab1/lab1/)\
Year: 2024\
Group: U4125\
Author: Gaptelganieva Guzel\
Lab: Lab2\
Date of create: 30.04.2024\
Date of finished: 03.05.2024

## Лабораторная работа №2 "Исследование Cloud Run"

### 1 
Создала Cloud Run из представленного дефолтного сервиса Hello с минимальным количеством ресурсов
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/d3f72b55-b50e-4605-bf14-635534631c2c)
### 2 
Перешла по ссылке Cloud Run
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/8290ceb5-198a-4a2e-8339-50c029b457ed)
### 3
Перешла во вкладку LOGS, вижу, как создался (первая строка) и развертывался Cloud Run, статус готовности к принятию им запросов (Hello from Cloud Run! The container started successfully and is listening for HTTP requests on $PORT), статусы входа пользователем (в самом низу)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/9b90a237-0576-4845-8766-fda712bb6227)
### 4
Перешла во вкладку METRICS, посмотрела изменение различных показателей, харарктеризующих работу контейнеров (Количество запросов, Задержки запросов, Количество экземпляров контейнера, Оплачиваемое время создания экземпляра контейнера, Загрузка процессора контейнера, Загрузка памяти контейнера, Отправленные байты, Полученные байты, Задержка запуска контейнера)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/af805883-7237-4453-8604-5b4456b52747)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/410ae292-774a-4a6d-9f9e-da41b6a098fd)
### 5
Меняю порт в контейнере на 8090
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/a6f2dc7e-c1a7-4c33-8eaf-bcf8f3e3b706)
Появилась вторая версия с другим названием, и по ссылке теперь открывается именно она
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/3f9ff127-d7ee-4113-8fe9-c3421573418c)
### 6
Переключаюсь между версиями и смотрю, как это влияет на метрики
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/e248f6a1-c8c2-442f-aac0-5a4e3d98b0c9)
Можно посмотреть развернутые графики и менять визуал
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/f5339441-4f64-4695-a343-4e7dc0b9e9f2)

### Таким образом, с помощью CLoud Run можно создавать и запускать собственный контейнер, отслеживать его работу с точки зрения нагрузки, различных изменений, активностей пользователей и возникающих ошибок
