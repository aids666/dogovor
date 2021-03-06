# Техническое задание разработку сайта. Общие положения и требования

## Назначение документа

В настоящем документе приводится полный набор требований к реализации сайта.
Подпись Заказчика и Исполнителя на настоящем документе подтверждает их согласие с нижеследующими фактами и условиями:

* Исполнитель подготовил и разработал настоящий документ, именуемый Техническое Задание, который содержит перечень требований к выполняемым работам.
* Заказчик согласен со всеми положениями настоящего Технического Задания.
* Заказчик не вправе требовать от Исполнителя в рамках текущего Договора выполнения работ либо оказания услуг, прямо не описанных в настоящем Техническом Задании.
* Исполнитель обязуется выполнить работы в объеме, указанном в настоящем Техническом Задании.
* Заказчик не вправе требовать от Исполнителя соблюдения каких-либо форматов и стандартов, если это не указано в настоящем Техническом Задании.
* Все неоднозначности, выявленные в настоящем Техническом задании после его подписания, подлежат двухстороннему соглашению между Сторонами. В процессе согласования могут быть разработаны дополнительные требования, которые оформляются дополнительным соглашением к Договору и соответствующим образом оцениваются.

## Требования к системе управления контентом (CMS)
Система управления контентом (административная часть сайта) должна предоставлять возможность добавления, редактирования и удаления содержимого статических и динамических страниц. Также должна быть предусмотрена возможность добавления информации без отображения на сайте.

Система управления контентом должна иметь стандартный интерфейс, отвечающий следующим требованиям:
* реализация в графическом оконном режиме;
* единый стиль оформления;
* интуитивно понятное назначение элементов интерфейса;
* отображение на экране только тех возможностей, которые доступны конкретному пользователю;
* отображение на экране только необходимой для решения текущей прикладной задачи информации;
* отображение на экране хода длительных процессов обработки;
* диалог с пользователем должен быть оптимизирован для выполнения типовых и часто используемых операций;
* для операций по массовому вводу информации должна быть предусмотрена минимизация количества нажатий на клавиатуру для выполнения стандартных действий.

## Требования к навигации на сайте.
Пользовательский интерфейс сайта должен обеспечивать наглядное, интуитивно понятное представление структуры размещенной на нем информации, быстрый и логичный переход к разделам и страницам. Навигационные элементы должны обеспечивать однозначное понимание пользователем их смысла: ссылки на страницы должны быть снабжены заголовками, условные обозначения соответствовать общепринятым. Графические элементы навигации должны быть снабжены альтернативной подписью.

Система должна обеспечивать навигацию по всем доступным пользователю ресурсам и отображать соответствующую информацию. Для навигации должна использоваться система контент-меню. Меню должно представлять собой текстовый блок (список гиперссылок) в левой колонке или в верхней части страницы (в зависимости от утвержденного дизайна).
Для разделов, содержащих подразделы, должно быть предусмотрено выпадающее подменю.
При выборе какого-либо из пунктов меню пользователем должна загружаться соответствующая ему информационная страница (новостная лента, форма обратной связи и пр.), а в блоке меню (или в основной части страницы в зависимости от утвержденного дизайна) открываться список подразделов выбранного раздела. 

## Требования к разделению доступа
Информация, размещаемая на сайте, является общедоступной.
Пользователей сайта можно разделить на 3 части в соответствии с правами доступа:
* Посетители
* Редактор (сотрудник Заказчика)
* Администратор (сотрудник Исполнителя)
Посетители имеют доступ только к общедоступной части сайта.

Доступ к административной части имеют пользователи с правами редактора и администратора.

Редактор может редактировать материалы разделов.

Администратор может выполнять все те же действия, что и Редактор, и кроме того:
* добавлять пользователей с правами Редактора;
* добавлять и удалять разделы сайта.
Доступ к административной части должен осуществляться с использованием уникального логина и пароля. Логин выдается администратором сайта. При создании пользователя в системе,  на его электронный адрес отправляется сообщение, в котором указана одноразовая ссылка входа, перейдя по которой система предлагает пользователю сменить пароль (ввести вручную новый пароль).

Для обеспечения защиты от несанкционированного доступа к административной части при составлении паролей рекомендуется придерживаться следующих правил:
* Длина пароля должна быть не менее 8 символов.
* Пароль должен состоять из цифр и латинских букв в разных регистрах; желательно включать в пароль другие символы, имеющиеся на клавиатуре (например, символы / ? ! < > [ ] { } и т.д.)
* Пароль не должен являться словарным словом или набором символов, находящихся рядом на клавиатуре. В идеале пароль должен состоять из бессмысленного набора символов.
* Все пароли необходимо менять с определенной периодичностью, оптимальный срок - от трех месяцев до года.

Все опубликованные разделы сайта должны открываться для доступа на чтение без аутентификации пользователя. При попытке входа в закрытый раздел у пользователя не прошедшего аутентификацию, должен быть запрошен логин и пароль. После прохождения аутентификации система должна проверять полномочия пользователя на доступ к запрошенному разделу. Если доступ запрещен, пользователю должно быть выведено сообщение о невозможности доступа в закрытый раздел. 

## Требования к видам обеспечения 
### Требования к хранению данных
Все данные сайта должны храниться в структурированном виде под управлением реляционной СУБД. Исключениями могут быть файлы данных, предназначенные для просмотра и скачивания (изображения, видео, документы и т.п.). Такие файлы сохраняются в файловой системе или в облачном хранилище, а в БД размещаются ссылки на них. Наполнение различных сайтов, функционирование которых поддерживается одной и той же инсталляцией системы, должно храниться под управлением единой СУБД.

Требования к прикрепленным файлам: 
- Максимальный размер файла: 25 МБ.
- Разрешённые типы файлов: txt, jpg, jpeg, png, doc, docx, pdf, ods, xlsx, xls, zip, rar
- Опция “отображение” у файла позволяет скрыть/отобразить его в списке внизу страницы.
- Максимальное количество прикрепленных файлов у одной страницы — 25.

### Требования к языкам программирования
* Для реализации статических страниц и шаблонов должны использоваться языки HTML 5 и CSS 3.
* Исходный код разрабатывается  руководствуясь  стандартами W3C.
* Для реализации интерактивных элементов клиентской части должны использоваться языки JavaScript и HTML.
* Для реализации динамических страниц должен использоваться язык PHP. 

### Требования к организации гиперссылок
Все ссылки на сайте должны быть относительными (за исключением внешних).

### Требования к иллюстрациям
Изображения, загружаемые через интерфейс управления дополняются замещающим текстом. Допускаются следующие форматы gif или jpg, png. 

### Требования к программному обеспечению серверной части 
Для функционирования сайта необходимо следующее программное обеспечение:
* Операционная система –Ubuntu 16.04;
* Веб-сервер – Nginx версии не ниже 1.13;
* СУБД – MySQL 5.5.3;
* PHP- 5.5.9 или выше

### Требования к клиентскому программному обеспечению
Сайт должен быть доступен для полнофункционального просмотра с помощью популярных браузеров последней версии

### Требования к хостингу
Сайт располагается на облачном хостинге, со следующей конфигурацией
* память - от 1 ГБ
* процессор - от 1 ядра
* дисковое пространство- от 100 МБ

### Требования к лингвистическому обеспечению
Сайт должен выполняться на русском языке. 

### Требования к эргономике и технической эстетике
Верстка Сайта должна быть адаптивной под разные разрешения экранов. Сайт должен отображаться без горизонтальной полосы прокрутки и без пустых (белых) полей для основных типов разрешений. Изменение расположения элементов сайта при адаптивной версии сайта происходят с учетом следующих параметров ширины экрана: <544px ,  ≥768px, ≥992px, ≥1200px. На каждой странице должны отображаться логотип компании и контактная информация. Сайт имеет единый интерфейс управления модулями и расширениями, и управлением материалами

## Требования к приемке-сдаче проекта
### Требования к наполнению информацией
Исполнитель обеспечивает приведение графических материалов в соответствие с техническими требованиями и обеспечивает HTML-верстку подготовленных материалов.

Сканирование, набор и правка-вычитка текстов, ретушь, монтаж, перевод и другие работы могут быть выполнены Исполнителем на основании дополнительного соглашения (после просмотра имеющихся у заказчика материалов).

После сдачи системы в эксплуатацию информационное наполнение разделов, осуществляется на основании договора на поддержку сайта. Объем текста и количество иллюстраций в других типах разделов определяется предусмотренной настоящим ТЗ структурой данных и уточняется на этапе согласования дизайн-концепции.

### Требования к верстке страниц
При разработке html-документ необходимо руководствоваться стандарту w3c. html-документ должен быть сверстан с применением CSS. html- документ сайта должен иметь блочную верстку (верстку div'ами), вложенные блоки следует отметить отступами, для отступов использовать табуляцию. html-код сайта должен быть удобен для понимания и структурирован, сложные и неоднозначные моменты прокомментированы.

Определение стилей непосредственно на странице недопустимо. Все java-скрипты следует хранить в папке /js/, вставка скриптов непосредственно в html-код не допустима, за исключением кода счетчика Google Analytics и ситуаций когда вынос скриптов в отдельный файл невозможен. Все названия стилей должны быть английскими (без русских слов на латинице). У всех ссылок должен быть прописан параметр title="". У всех картинок должен быть прописан параметр alt="". Не следует использовать на странице заголовки h2 если нет заголовка h1 (это касается всех уровней заголовков). Не использовать на странице более одного заголовка h1. 

Страница должна максимально идентично отображаеться во всех современных браузерах последних версий.

### Требования к документации
В момент сдачи проекта заказчику предоставляется следующий набор документов: 
* Техническое задание на разработку сайта.
* Документация по стандартным модулям системы управления сайтом ITCMS.
* Краткое руководство (справочная информация) пользователя в административной части сайта.Предусматривается обучение 1-2 представителей заказчика в течении 2 часов

Руководство по переносу системы на другую хостинг - площадку не предоставляется.

### Требования к персоналу
Для эксплуатации веб-интерфейса системы динамического управления наполнением от администратора не должно требоваться специальных технических навыков, знания технологий или программных продуктов, за исключением общих навыков работы с персональным компьютером и стандартным веб-браузером.

Администратор, оператор: уверенный пользователь сети Интернет, знание Microsoft Word. Прочие пользователи: уверенный пользователь сети Интернет.

### Порядок предоставления дистрибутива
По окончании разработки Исполнитель должен предоставить Заказчику дистрибутив системы в составе:
* архив с исходными кодами всех программных модулей и разделов сайта;
* дамп проектной базы данных с актуальной информацией. Дистрибутив предоставляется на виде файлового архива по электронной почте. 

### Порядок переноса сайта на технические средства Заказчика
После завершения сдачи-приемки сайта, Заказчиком самостоятельно производится перенос разработанного программного обеспечения на аппаратные средства Заказчика. Соответствие программно-аппаратной платформы требованиям настоящего документа обеспечивает Заказчик.
Исполнитель передает заказчику архив сайта: База данных, файловую систему посредством передачи ссылки на скачивание архива. Логин и пароль для администратора передаются в электронном письме Заказчику.

## Порядок контроля и приемки сайта
### Порядок приемки дизайн-концепции
Под дизайн-концепцией понимается вариант оформления главной страницы и графическая оболочка внутренних страниц, демонстрирующие общее визуальное (композиционное, цветовое, шрифтовое, навигационное) решение основных страниц сайта.

Дизайн-концепция представляется в виде файла (нескольких файлов) в растровом формате или в распечатке по согласованию сторон.
Если представленная Исполнителем дизайн-концепция удовлетворяет Заказчика, он должен утвердить ее в течение пяти рабочих дней с момента представления. При этом он может направить Исполнителю список частных доработок, не затрагивающих общую структуру страниц и их стилевое решение. Указанные доработки производятся параллельно с разработкой программных модулей сайта. Внесение изменений в дизайн-концепцию после ее приемки допускается только по дополнительному соглашению сторон.

Если представленная концепция не удовлетворяет требованиям Заказчика, последний предоставляет мотивированный отказ от принятия концепции с указанием деталей, которые послужили препятствием для принятия концепции и более четкой формулировкой требований. В этом случае Исполнитель разрабатывает второй вариант дизайн-концепции (дорабатывает, вносит изменения). Обязательства по разработке второго варианта дизайн-концепции Исполнитель принимает только после согласования и подписания дополнительного соглашения о продлении этапа разработки дизайн-концепции на срок не менее пяти рабочих дней.

Дополнительные (третий и последующие) варианты разрабатываются Исполнителем за отдельную плату на основании дополнительных соглашений. 

### Виды, состав, объем и методы испытаний
Сдача-приемка выполненных работ должна осуществляться при предъявлении Исполнителем комплектов соответствующих документов и завершаться оформлением акта сдачи-приемки, подписанного Исполнителем и утвержденного Заказчиком.

Испытания сайта проводятся силами Исполнителя.

### Общие требования к приемке сайта
Приемка сайта должна проводиться приемочной комиссией, в состав которой должны входить представители Заказчика и Исполнителя, в течение трех рабочих дней после завершения работ. Результаты работы комиссии должны оформляться актом, подписанным членами комиссии и утвержденным Заказчиком.

## Требования к составу и содержанию работ по вводу сайта в эксплуатацию
Для переноса сайта на хостинг необходимо, чтобы параметры хостинга соответствовали требованиям, указанным в настоящем ТЗ. На хостинг переносится программа (сайт), сверстанный шаблон дизайна и структура и наполнение базы данных. Перенос данных осуществляется силами Заказчика.
