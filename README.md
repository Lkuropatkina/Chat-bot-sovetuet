# Chat-bot-sovetuet
Курсовая работа третий курс, одиночный программный проект. Большая задача - создание чатбота, который предлагает подарок описанному человеку. 

`*Результаты:*` собраны данные, разработана методология опроса, создана эффективная модель, распланированы дальнейшие действия.

+ load_data - код парсинга Яндекс.Маркета, выгрузка подкатегорий

+ categoria.txt - выгруженные подкатегории, названия текстовой строкой (на данный момент сайт уже немного поменялся и там другие)

+ choose_categories - код обработки двух опросов, к концу получаем матрицу данных, на которой будет обучатся модель

+ final_opros - полученный датасет, на котором обучается модель 

+ machine_learning - обучение классификатора, регрессора, оценка их качества. Выбираем модель регрессора

+ finalized_model - готовая модель

+ parsing2 - незаконченный файл, по плану тут произойдет парсинг сайта второй. Название подобранной категории вводится в поиск, парсятся 

первые товары, и подошедшие по цене предлагаются
