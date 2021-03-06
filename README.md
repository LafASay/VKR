# VKR
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
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A0.jpg)

Ветка А1-А3:
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A1.jpg)

Ветка А11-А13:
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A11.jpg)

Ветка А21-А23:
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A21.jpg)

Ветка А31-А33:
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A31.jpg)


### Лабораторная работа 5
 DFD диаграммы курсового проекта
1. Определение основных средств автоматизации:
Определение конфигурации технических средств (рабочие станции, серверы, другое оборудование) - Устройства с возможностью работы в браузере и выходом в интернет.

Определение конфигурации программных средств (одноуровневые, многоуровневые, встроенные, распределенные) - Многоуровневая архитектура.

Определение допустимых видов хранилищ и их размещения - БД.

2. Разработка диаграмм в RAMUS
Декомпозиция всех автоматизируемых блоков в DFD 

#Декомпозиция блока A31(Определение лучших курсов): 
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A331.jpg)

#Декомпозиция блока A32(Формирование графиков): 
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A332.jpg)

#Декомпозиция блока A33(Формирование отчета): 
![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/A333.jpg)

Построение ![ERD](https://github.com/LafASay/-Frolov-.github.io/blob/master/Rol)  для всех ролей:

![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/%D0%A0%D0%BE%D0%BB%D1%8C.png)

Построение ![ERD](https://github.com/LafASay/-Frolov-.github.io/blob/master/potoki) для всех потоков:

![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8.png)

Построение ![ERD](https://github.com/LafASay/-Frolov-.github.io/blob/master/modul) для всех модулей:

![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/%D0%9C%D0%BE%D0%B4%D1%83%D0%BB%D1%8C1.png)

### Рассчет данных

Данная информационная система позволяет наиболее быстро и эффективно добывать нобходимую информацию со сторонних информационнх ресурсов, стрктурировать их и предоставлять в упорядоченном виде. В данном примере, рассмотрен поиск информации по наивыгоднейшему курсу валют для рядового пользователя сети "Интенет".

•	Без системы: Для того, чтобы польователю проанализировать самостоятельно для себя, где для него бует выгоден курс валют на день обмена, ему необходимо зайти самостоятльно на сайт банка, на нем найти нобходимую вкладку с информацией о урсе валют в этом банке, где-то у себя сохрранить эту информацию (для дальнешего сравнения с другими банками). В  среднем, на эти действия уходит обчно не менее 5 минут. При том, что пользователь вынужден тратить свое время не на один сайт банка, а мнимум на 5. Зачастую, пользователи запрашивают информацию только по хорошо знакомым банкам, которые "на слуху". и как следствие - курсы валют в таких банках зачастую е отличаются своей "выгодностью" для конечного потребителя.  Слеовательно. пользователь не только тратит свое время на поиск той информации, которую можно автоматиизовать, но и зачастую не находит наивыгоднейшего результата. 

•	С системой: Благодаря отсутствию понятия "на слуху", с автоматизацией процесса поиска валют мы получаем намного больше непредвзятой инфомации по предоставляемым услугам. Удобная подача информации и отсутствие необходимости самостоятельного сравнения результатов поиска позволяет быстро определить как раз "наилучший" вариант обмена для польователя. На поиск будет уходить существенно меньше времени. Если без системы в среднем, пользователь тратит по 25-30 минут своего времени, то с системой он потатит  минут - это то же самое врмя, которое необходимо пользователю для посещения сайта и обнаружении а главной странице наилучших варантов.

Эффективность работы в среднем увеличивается в 25/5=5 раз! На практике это означает, что система помогает существенно экономить пользователю время, которое он отводит на поиск информации. При этом качество обнаружения наиболее выгодного варанта не только не пострадает ,но и значительно возрастет, так как автоматизированная система исключает возможность сбора инфомации только по банкам, входящив в ТОП по рекламе на рынке услуг, уделяет внимание по сбору информации каждого банка и позволяет не просто собрать информацию по курсу, но и опреелить наилучший результат, необходимый пользователю.


![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/111111.png)

Рассчет сложности разработки методом FPA/IFUG

![Текст](https://github.com/LafASay/VKR/blob/master/%D1%82%D1%80%D1%83%D0%B41.png)

Рассчет трудозатрат на разработку методом COCOMO

![Текст](https://github.com/LafASay/-Frolov-.github.io/blob/master/cocomo.png)
