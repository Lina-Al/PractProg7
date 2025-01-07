# PractProg7

В данном документе будет описан ход работы. 

 1. Создание проекта с помощью Spring Initializr
 • Откройте Spring Initializr.
 • Выберите следующие параметры:– Project: Maven– Language: Java– Spring Boot version: последняя стабильная версия.– Dependencies: Spring Web, Spring Data JPA, H2 Database.
 • Скачайте и импортируйте проект в IDE (IntelliJ IDEA, VSCode, Eclipse (если надо помучаться))

Задание: 

Был создан проект и загружен в VSCode: 
![image](https://github.com/user-attachments/assets/76470e3a-5892-4ef8-98f2-529db08874aa)

А так же был установлен SDKMAN.

Далее был установллен по умолчании JDK 

![image](https://github.com/user-attachments/assets/a89db033-558e-4d32-99e2-46bc00d55975)

Настройка базы данных: Открываем файл  application.yml (до этого меняя расширение на yml) и добавленяем безопасность:

![image](https://github.com/user-attachments/assets/1a313b48-8de2-4b03-8b01-cb0e8596de5a)

Создание модели задачи:

![image](https://github.com/user-attachments/assets/b3439152-8d57-40af-bc32-41365092d05c)

Создание репозитория для зада:
 Создаtv интерфейс TaskRepository, наследующий от JpaRepository, для доступа к данным
 
![image](https://github.com/user-attachments/assets/32588b69-2bf1-4c65-94ee-cfdeb01b909d)

Создание REST контроллера: 

![image](https://github.com/user-attachments/assets/2137b975-70a2-4d32-8173-867f7c2fb65d)

Запустим приложение, тем самым проверив его работу: 

![image](https://github.com/user-attachments/assets/854957ea-70a1-41c9-90f3-ea4acefb5590)

Тестирование приложения: 

Зайдем по ссылке /h2-console и заполним поля:

![image](https://github.com/user-attachments/assets/2dbd81f9-1df8-4148-89a1-b2e949be1c8a)

