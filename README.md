# VKR2019
Тема ВКР: Разработка WEB-сервиса с использованием методов сбора, обработки  и анализа неструктурированных данных.

Объект исследований: технические средства сбора, обработки и анализа данных.

Предмет исследований: современные информационные ресурсы применимые для определения выгодных курсов валют на банковском рынке в сети "Интернет".

Процессы верхнего уровня:

А1 Сбор данных (относится к внешней среде; обеспечивает систему необходимой информацией и сбором данных в базу).

А2 Подготовка данных (относится к внутренней среде; приведение полученных данных к единому виду).

А3 Вывод данных о курсах валют (относится к внутренней среде; анализ, обработка и структурирование данных).


### Лабораторная работа 4
Декомпозиция автоматизируемых блоков до уровня, прямо сопоставляемого с программными модулями

Ветка А0:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/A02.png)

Ветка А1-А4:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/A1-3.png)

Ветка А11-А13:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B011.png)

Ветка А21-А23:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B021-23.png)

Ветка А31-А33:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/A3133(2).png)

Ветка А41-А43:
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A1%D0%B5%D1%80%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%82.png)

### Лабораторная работа 5
 DFD диаграммы курсового проекта
1. Определение основных средств автоматизации:
Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование) - Рабочие станции (ПК), сервер.

Определение конфигурации программных средств (одноуровневые, многоуровневые, встроенные, распределенные) - Многоуровневая.

Определение допустимых видов хранилищ и их размещения - БД.

2. Разработка диаграмм в RAMUS
Декомпозиция всех автоматизируемых блоков в DFD 

#Декомпозиция блока A31(генерация задания): 
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B031dfd.png)

#Декомпозиция блока A32(Выполнение задания): 
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B032dfd.png)

#Декомпозиция блока A33(Проверка и интеллектуальный анализ выполнения): 
![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%B033dfd.png)

Построение ![ERD](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A0%D0%BE%D0%BB%D0%B8%D0%A2%D0%B5%D0%BA%D1%81%D1%82)  для всех ролей:

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A0%D0%BE%D0%BB%D0%B8.png)

Построение ![ERD](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%9F%D0%BE%D1%82%D0%BE%D0%BA%D0%B8%D0%A2%D0%B5%D0%BA%D1%81%D1%82) для всех потоков:

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8.png)

Построение ![ERD](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%9C%D0%BE%D0%B4%D1%83%D0%BB%D0%B8) для всех модулей:

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/jLNDgjD055xVUOhXxkyRkBZMXt0Tas13aqOcAIvKw8zKeGj513TIKDmAwKziIDhq5SuyYQ_WbqdQnDZQeN0fbEPyFz_CoJdqFWWD4Guyb_tEzYpeEVqNXZ0yRhf64F1NxAPZcBtdmX_qhIU-wml-jEk4DhjvB8J_ignqN510z8LbYsRf3IjTw2lbj9OJoYYfIhVqar8vf8Xs-4Jo0vTlAKTXIz7j.png)

### Рассчет данных

Данная информационная система позволяет наиболее быстро и эффективно добывать нобходимую информацию со сторонних информационнх ресурсов, стрктурировать их и предоставлять в упорядоченном виде. В данном примере, рассмотрен поиск информации по наивыгоднейшему курсу валют для рядового пользователя сети "Интенет".

•	Без системы: Для того, чтобы польователю проанализировать самостоятельно для себя, где для него бует выгоден курс валют на день обмена, ему необходимо зайти самостоятльно на сайт банка, на нем найти нобходимую вкладку с информацией о урсе валют в этом банке, где-то у себя сохрранить эту информацию (для дальнешего сравнения с другими банками). В  среднем, на эти действия уходит обчно не менее 5 минут. При том, что пользователь вынужден тратить свое время не на один сайт банка, а мнимум на 5. Зачастую, пользователи запрашивают информацию только по хорошо знакомым банкам, которые "на слуху". и как следствие - курсы валют в таких банках зачастую е отличаются своей "выгодностью" для конечного потребителя.  Слеовательно. пользователь не только тратит свое время на поиск той информации, которую можно автоматиизовать, но и зачастую не находит наивыгоднейшего результата. 

•	С системой: Благодаря отсутствию понятия "на слуху", с автоматизацией процесса поиска валют мы получаем намного больше непредвзятой инфомации по предоставляемым услугам. Удобная подача информации и отсутствие необходимости самостоятельного сравнения результатов поиска позволяет быстро определить как раз "наилучший" вариант обмена для польователя. На поиск будет уходить существенно меньше времени. Если без системы в среднем, пользователь тратит по 25-30 минут своего времени, то с системой он потатит  минут - это то же самое врмя, которое необходимо пользователю для посещения сайта и обнаружении а главной странице наилучших варантов.

Эффективность работы в среднем увеличивается в 25/5=5 раз! На практике это означает, что система помогает существенно экономить пользователю время, которое он отводит на поиск информации. При этом качество обнаружения наиболее выгодного варанта не только не пострадает ,но и значительно возрастет, так как автоматизированная система исключает возможность сбора инфомации только по банкам, входящив в ТОП по рекламе на рынке услуг, уделяет внимание по сбору информации каждого банка и позволяет не просто собрать информацию по курсу, но и опреелить наилучший результат, необходимый пользователю.


![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5.png)

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/KLOK.png)

![Текст](https://github.com/DenisKolgatin/SkladForCurs/blob/master/%D0%A1oco.png)
