# Домашнее задание к занятию «Конфигурация приложений» - `Мальцев Виктор`

---

Задание 1. Создать Deployment приложения и решить возникшую проблему с помощью ConfigMap. Добавить веб-страницу

    1. Создать Deployment приложения, состоящего из контейнеров nginx и multitool.
    2. Решить возникшую проблему с помощью ConfigMap.
    3. Продемонстрировать, что pod стартовал и оба конейнера работают.
    4. Сделать простую веб-страницу и подключить её к Nginx с помощью ConfigMap. Подключить Service и показать вывод curl или в браузере.
    5. Предоставить манифесты, а также скриншоты или вывод необходимых команд.


Ответ:

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_143.png)

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_144.png)

Манифесты доступны по ссылке https://github.com/vmmaltsev/kuber-homeworks-2.3/tree/main/1

------

Задание 2. Создать приложение с вашей веб-страницей, доступной по HTTPS

    1. Создать Deployment приложения, состоящего из Nginx.
    2. Создать собственную веб-страницу и подключить её как ConfigMap к приложению.
    3. Выпустить самоподписной сертификат SSL. Создать Secret для использования сертификата.
    4. Создать Ingress и необходимый Service, подключить к нему SSL в вид. Продемонстировать доступ к приложению по HTTPS.
    5. Предоставить манифесты, а также скриншоты или вывод необходимых команд.

Ответ:

![alt text](https://github.com/vmmaltsev/screenshot/blob/main/Screenshot_145.png)

Манаифесты доступны по ссылке https://github.com/vmmaltsev/kuber-homeworks-2.3/tree/main/2

