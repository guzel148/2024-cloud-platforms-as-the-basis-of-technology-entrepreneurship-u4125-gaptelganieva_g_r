University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2024
Group: U4125
Author: Gaptelganieva Guzel
Lab: Lab1
Date of create: 30.04.2024
Date of finished:



## 1 
В разделе Identity and Access Management (IAM) создала Service Account 
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/13ee7ae2-2da1-47e3-9d91-9c26f7e8e60c)
## 2 
Установила себе роль Storage Admin (расширенный функционал)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/e2441c1d-c3e7-4def-8a79-1e0a5fd758af)
## 3 
В разделе Computer Engine создала виртуальную машину с Machine type e2-micro в режиме spot, привязав ее к своему Service Account
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/15b08685-e403-474b-97f9-da04c63d599e)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/076543b4-dd8c-4999-a532-c31153558d56)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/5e2d9f59-6ea9-4110-89bb-1449d82689e5)
## 4 
Нажала на кнопку SSH ((Secure Shell, метод безопасного доступа и управления виртуальными машинами) и с помощью команды gsutil скопировала из бакета lab1-bucket-itmo. C помощью команды ls -lah проверила, что файлы переместились в виртуальную машину
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/c36a0b9e-66a5-4525-9739-e03d1d17a8bb)
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/d8f6316a-3ea2-4203-a8e4-8adf9d4195cf)
## 5
Вернулась в IAM и поменяла Service Account с Storage Admin на Compute Viewer (роль с ограниченным доступом) 
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/305b9bc0-7f93-4706-972d-5dac80c747de)
## 6
Зашла в Computer Engine SSH. Теперь уже не получается это сделать, так как роль Compute Viewer не дает таких прав.
![image](https://github.com/guzel148/2024-cloud-platforms-as-the-basis-of-technology-entrepreneurship-u4125-gaptelganieva_g_r/assets/156536395/5f8b21e6-5c7b-44c4-8a29-04b382c8786b)
