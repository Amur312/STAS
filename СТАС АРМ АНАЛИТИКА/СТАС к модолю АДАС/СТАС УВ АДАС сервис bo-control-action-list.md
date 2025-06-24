<p><ac:structured-macro ac:name="toc" ac:schema-version="1" ac:macro-id="dfd06b50-f322-4d47-9bbc-5750338929f6" /></p><ac:structured-macro ac:name="numberedheadings" ac:schema-version="1" ac:macro-id="07a00a23-bb8d-41b3-afbc-c102f657467c"><ac:rich-text-body>
<h1 style="text-decoration: none;">Глоссарий</h1>
<table class="relative-table wrapped" style="width: 709.4792px;">
<thead style="text-decoration: none;">
<tr>
<th style="text-align: left;">
<p>Термин</p></th>
<th style="text-align: left;">
<p>Определение</p></th></tr></thead><colgroup style="text-decoration: none;"><col style="width: 0.0px;" /><col style="width: 0.0px;" /></colgroup>
<tbody style="text-decoration: none;">
<tr>
<td style="text-align: left;">АДАС</td>
<td style="text-align: left;">Автоматическое добавление и удаление значений атрибутов транзакции в списки</td></tr>
<tr>
<td colspan="1">УВ</td>
<td colspan="1">Управляющее воздействие</td></tr></tbody></table>
<h1>История изменений</h1>
<table class="wrapped"><colgroup><col style="width: 38.0px;" /><col style="width: 497.0px;" /><col style="width: 277.0px;" /><col style="width: 148.0px;" /></colgroup>
<tbody>
<tr>
<th>№</th>
<th>Изменения</th>
<th>Автор</th>
<th colspan="1">Дата</th></tr>
<tr>
<td>1</td>
<td>
<p>Изменена обязательность при передачи в кафку для следующих полей, т.к. они не доступны для редактирования если действие шаблона = Удалить:</p>
<p>Время жизни значения атрибута в списке (в минутах)</p>
<p><span style="color: rgb(0,51,102);">Смещение старта времени жизни значения атрибута в списке (в минутах)</span></p>
<p><span style="color: rgb(0,51,102);">Было:&nbsp;<span style="color: rgb(0,0,0);">обязательно</span></span></p>
<p><span style="color: rgb(0,51,102);"><span style="color: rgb(0,0,0);">Стало:&nbsp;необязательно</span></span></p></td>
<td>
<div class="content-wrapper">
<p><ac:link><ri:user ri:userkey="8aa405e56e670730016e695c60670008" /></ac:link></p></div></td>
<td colspan="1">
<div class="content-wrapper">
<p><time datetime="2022-10-20" />&nbsp;</p></div></td></tr>
<tr>
<td colspan="1">2</td>
<td colspan="1">
<p><span style="color: rgb(23,43,77);">Данные в кафку отправляются по правилам в любом статусе у которых есть связь с шаблоном АДАС</span></p>
<p>Было, только по активным правилам</p></td>
<td colspan="1"><ac:link><ri:user ri:userkey="8aa405e56e670730016e695c60670008" /></ac:link></td>
<td colspan="1">
<div class="content-wrapper">
<p><time datetime="2022-10-21" />&nbsp;</p></div></td></tr>
<tr>
<td colspan="1">3</td>
<td colspan="1">Если списков в шаблоне нет - команда delete не отправляется</td>
<td colspan="1">
<div class="content-wrapper">
<p><ac:link><ri:user ri:userkey="8aa405e56e670730016e695c60670008" /></ac:link></p></div></td>
<td colspan="1">
<div class="content-wrapper">
<p><time datetime="2022-10-24" />&nbsp;</p></div></td></tr>
<tr>
<td colspan="1">4</td>
<td colspan="1">
<p>Добавлено:</p>
<ul>
<li>п. 3.3.4 Схема взаимодействия при удалении списка из Модуля списков, связанного с шаблоном АДАС.</li>
<li>п. 3.3.5&nbsp;Схема взаимодействия при удалении правила из Модуля правил, связанного с шаблоном АДАС.</li>
<li>передача списка id списка + attributeName</li>
<li>control-action-list-kafka-spec</li></ul>
<p>Обновлено&nbsp;</p>
<ul>
<li>Требования к программным&nbsp;интерфейсам</li></ul></td>
<td colspan="1"><ac:link><ri:user ri:userkey="8aa405e56e670730016e695c60670008" /></ac:link></td>
<td colspan="1">
<div class="content-wrapper">
<p><time datetime="2022-10-27" />&nbsp;</p></div></td></tr>
<tr>
<td colspan="1">5</td>
<td colspan="1">В п 4.3.1 добавил: core-control-action-list&nbsp;</td>
<td colspan="1"><ac:link><ri:user ri:userkey="8aae6c948041352f01804172de8b0009" /></ac:link></td>
<td colspan="1">
<div class="content-wrapper">
<p><time datetime="2022-12-21" />&nbsp;</p></div></td></tr>
<tr>
<td colspan="1">6</td>
<td colspan="1">в п 3.2.2 Добавлено: примечание об отправке с<span style="color: rgb(23,43,77);">ервиса bfp-bo-policy-list </span></td>
<td colspan="1">
<div class="content-wrapper">
<p><ac:link><ri:user ri:userkey="8aae6c948041352f01804172de8b0009" /></ac:link></p></div></td>
<td colspan="1">
<div class="content-wrapper">
<p><time datetime="2022-12-21" />&nbsp;</p></div></td></tr></tbody></table>
<h1>Общие сведения</h1>
<h2 style="text-decoration: none;">Ссылка Jira</h2>
<p><ac:structured-macro ac:name="jira" ac:schema-version="1" ac:macro-id="f5f08a5a-55ed-45bd-9ad8-121b71a6cc67"><ac:parameter ac:name="server">Jira SberWorks</ac:parameter><ac:parameter ac:name="columnIds">issuekey,summary,issuetype,created,updated,duedate,assignee,reporter,priority,status,resolution</ac:parameter><ac:parameter ac:name="columns">key,summary,type,created,updated,due,assignee,reporter,priority,status,resolution</ac:parameter><ac:parameter ac:name="serverId">611daf70-25e6-3844-a434-3583e234ac1b</ac:parameter><ac:parameter ac:name="key">UINAF-247</ac:parameter></ac:structured-macro></p>
<h2 style="text-decoration: none;">Описание доработки</h2>
<p>Сервис УВ АДАС&nbsp;bo-control-action-list необходим для обновления содержимого списков при срабатывании связанных правил.&nbsp;</p>
<p>Для создания данного сервиса реализован следующий справочник:</p>
<ul>
<li>Шаблоны АДАС (сервис, в котором настраиваются параметры шаблона АДАС)</li></ul>
<p><ac:placeholder>Цель и кратко что создается/что изменяется</ac:placeholder></p>
<h2>Схемы взаимодействия&nbsp;</h2>
<h3>Общая схема взаимодействия BO и Core</h3>
<p><ac:structured-macro ac:name="drawio" ac:schema-version="1" ac:macro-id="930dcacb-570a-4e20-9a0f-ea9609f8ff22"><ac:parameter ac:name="border">true</ac:parameter><ac:parameter ac:name="diagramName">Взаимод</ac:parameter><ac:parameter ac:name="simpleViewer">false</ac:parameter><ac:parameter ac:name="width" /><ac:parameter ac:name="links">auto</ac:parameter><ac:parameter ac:name="tbstyle">top</ac:parameter><ac:parameter ac:name="lbox">true</ac:parameter><ac:parameter ac:name="diagramWidth">1098</ac:parameter><ac:parameter ac:name="revision">8</ac:parameter><ac:parameter ac:name="" /></ac:structured-macro></p>
<h4>Компоненты:</h4>
<ol>
<li>АРМ:
<ol>
<li>bo-policy-list&nbsp;- сервис списков;</li>
<li>bo-control-action-list - сервис управляющих воздействий;</li>
<li>Postgres -&nbsp;хранилище АРМ.</li></ol></li>
<li>Ядро:
<ol>
<li><span style="color: rgb(51,153,102);">core-control-action-list -&nbsp;сервис применения шаблонов добавления элементов в списки;</span></li>
<li><span style="color: rgb(51,153,102);">core-list-item-sync - сервис обновления элементов в списках АРМ.</span></li></ol></li></ol>
<h4>Потоки взаимодействия:</h4>
<ol>
<li><br />
<ol>
<li>core-control-action-list загружает начальное состояние шаблонов из bo-control-action-list;</li>
<li>bo-control-action-list&nbsp;создает команды обновления шаблонов.</li></ol></li>
<li>core-control-action-list обновляет состояние шаблонов на основе команд от bo-control-action-list;</li>
<li>core-control-action-list получает события с информацией о сработках правил;</li>
<li><br />
<ol>
<li>core-control-action-list применяет шаблоны к событию;</li>
<li>core-control-action-list формирует команду на обновление элементов списка в АРМ;</li>
<li>core-control-action-list формирует команду на обновление элементов списка в ядро;</li></ol></li>
<li>core-list-item-sync&nbsp;читает команды на&nbsp;добавление/удаление элементов списка АРМ&nbsp;</li>
<li>bo-policy-list&nbsp;добавляет/удаляет элементы списка в хранилище АРМ;<span>|</span></li>
<li>bo-policy-list формирует команды в ядро на обновление элементов списка при пользовательских действиях;</li>
<li>fact-engine читает команды на добавление/удаление элементов списка в ядре</li>
<li>fact-engine&nbsp;добавляет/удаляет элементы списков в Ignite (<span style="color: rgb(23,43,77);">очистка записей в ядре будет по TTL, который ранее реализован был)</span></li></ol>
<p><ac:placeholder> Тут вставляем сиквенс для модуля. Если меняются какие-то шаги с предыдущей реализации - явно подсвечиваем</ac:placeholder></p>
<h3><ac:inline-comment-marker ac:ref="99c1003e-aaa3-4099-acaf-638d6c71a71c">Схема взаимодействия</ac:inline-comment-marker> <ac:inline-comment-marker ac:ref="29093072-e8c8-4c94-b903-a1216f6006e9">для создания/редактирования/у</ac:inline-comment-marker><ac:inline-comment-marker ac:ref="917105e6-253b-477f-af0c-3a2dafa763f8"><ac:inline-comment-marker ac:ref="29093072-e8c8-4c94-b903-a1216f6006e9">даления/просмотра шаблона АДАС.</ac:inline-comment-marker></ac:inline-comment-marker></h3><ac:structured-macro ac:name="plantuml" ac:schema-version="1" ac:macro-id="7ad49d48-ba56-434c-99b5-f87630f1b4a8"><ac:parameter ac:name="atlassian-macro-output-type">INLINE</ac:parameter><ac:plain-text-body><![CDATA[@startuml
autonumber
skinparam ParticipantPadding 20
skinparam BoxPadding 20
skinparam maxmessagesize 200
skinparam shadowing false
autonumber

participant BBCAL as "bfp-bo-control-action-list"
participant BCCAL as "bfp-core-control-action-list"
BCCAL-->BBCAL:Запрос конфигураций шаблона АДАС
BBCAL->BCCAL:Возврат конфигураций

box "UI ARM.Front-end" #Lightblue 
actor "Analytic"
participant AFE as "ARM front-end"
activate Analytic
Analytic->AFE: Запрос на добавление/редактирование/удаление шаблона АДАС
end box

participant BBCAL as "bfp-bo-control-action-list"
activate AFE
AFE->NGINX:Вызов bfp-bo-control-action-list https/rest/json
deactivate AFE
activate NGINX
NGINX->NGINX:Фильтр запроса
NGINX->BBCAL:Маршрутизация к сервису bfp-bo-control-action-list https/rest/json
deactivate NGINX
participant NGINX

box "ARM.Back-end" #Lightgreen
participant BBCAL as "bfp-bo-control-action-list"
database BOS as "back-office storage"
participant BBPL as "bfp-bo-policy-list"
participant BBPR as "bfp-bo-policy-rule"

activate BBCAL
activate BOS
BBCAL->BOS:Запрос конфигураций шаблона АДАС
BOS-->BBCAL:Возврат конфигураций
group **Ошибка.Остановка процесса**
BOS-->BBCAL: Ошибка
BBCAL-->NGINX: Ошибка
NGINX-->AFE: Ошибка
AFE-->Analytic:Сообщение об ошибке 
end 
deactivate BOS
end box
deactivate BBCAL

AFE-->Analytic:Отображение в UI форм добаления/редактирования/удаления шаблона АДАС 
Analytic->AFE: Добавление/редактирование/удаление шаблона АДАС
AFE->NGINX: Вызов bfp-bo-control-action-list https/rest/json
activate NGINX
NGINX->NGINX:Фильтр запроса
NGINX->BBCAL:Маршрутизация к сервису bfp-bo-control-action-list https/rest/json
deactivate NGINX

activate BBCAL
activate BOS
BBCAL->BOS:Запрос на изменение конфигурации удаление/создание шаблона АДАС rest/json
BOS->BOS:Изменение конфигурации/удаление/создание
BOS-->BBCAL:Тех.квитанция
group **Ошибка.Остановка процесса** 
BOS-->BBCAL: Ошибка 
BBCAL-->NGINX: Ошибка
NGINX-->AFE: Ошибка
BBCAL-->Analytic:Сообщение об ошибке
end 
deactivate BOS
deactivate BBCAL

activate BBCAL
BBCAL->BBPL:Нотификация о привязке/удалении списков в шаблоне АДАС https/rest/json
BBPL-->BBCAL:Тех.квитанция
group **Ошибка.Остановка процесса**
BBPL-->BBCAL: Ошибка 
BBCAL-->NGINX: Ошибка
NGINX-->AFE: Ошибка
BBCAL-->Analytic:Сообщение об ошибке
deactivate BBCAL
end 

activate BBCAL
BBCAL->BBPR:Нотификация о привязке/удалении правил в шаблоне АДАС https/rest/json
BBPR-->BBCAL:Тех.квитанция
group **Ошибка.Остановка процесса**
BBPR-->BBCAL: Ошибка 
BBCAL-->NGINX: Ошибка
NGINX-->AFE: Ошибка
BBCAL-->Analytic:Сообщение об ошибке
deactivate BBCAL
end 

participant KF as "kafka"
participant BCCAL as "bfp-core-control-action-list"
BBCAL->KF:Публикация изменений по шаблону АДАС
BCCAL->KF:Вычитка изменений по шаблону АДАС

box "Antifraud Core" #Lightyellow
participant BCCAL as "bfp-bo-control-action-list"
end box

BBCAL-->Analytic:Вывод нового/отредактированного шаблона АДАС/сообщения об удалении 

@enduml]]></ac:plain-text-body></ac:structured-macro><ac:structured-macro ac:name="note" ac:schema-version="1" ac:macro-id="1f784655-12af-4e54-bbc5-34f0a1051e40"><ac:rich-text-body>
<p><span style="color: rgb(23,43,77);">Сервис bfp-bo-policy-list отправляет запрос в сервис&nbsp;bo-control-action-list при удалении списка для удалении связи шаблона АДАС со списком и аналогично&nbsp;bfp-bo-policy-rule отправляет запрос в сервис bo-control-action-list при удалении правила</span></p></ac:rich-text-body></ac:structured-macro>
<p><br /></p>
<h3>Схема взаимодействия для просмотра шаблона АДАС</h3><ac:structured-macro ac:name="plantuml" ac:schema-version="1" ac:macro-id="4618e68b-a081-49f3-953f-5c347a38f351"><ac:parameter ac:name="atlassian-macro-output-type">INLINE</ac:parameter><ac:plain-text-body><![CDATA[@startuml
autonumber
skinparam ParticipantPadding 20
skinparam BoxPadding 20
skinparam maxmessagesize 200
skinparam shadowing false
autonumber

box "UI ARM.Front-end" #Lightblue 
actor "Analytic"
participant AFE as "ARM front-end"
activate Analytic
Analytic->AFE: Запрос на просмотр шаблона АДАС
end box

participant BBCAL as "bfp-bo-control-action-list"
activate AFE
AFE->NGINX:Вызов bfp-bo-control-action-list https/rest/json
deactivate AFE
activate NGINX
NGINX->NGINX:Фильтр запроса
NGINX->BBCAL:Маршрутизация к сервису bfp-bo-control-action-list https/rest/json
deactivate NGINX
participant NGINX

box "ARM.Back-end" #Lightgreen
participant BBCAL as "bfp-bo-control-action-list"
database BOS as "back-office storage"

activate BBCAL
activate BOS
BBCAL->BOS:Запрос состояния шаблона АДАС
BOS-->BBCAL:Возврат конфигураций
group **Ошибка.Остановка процесса**
BOS-->BBCAL: Ошибка 
BBCAL-->NGINX: Ошибка
NGINX-->AFE: Ошибка
BBCAL-->Analytic:Сообщение об ошибке 
end 
deactivate BOS
end box


BBCAL-->Analytic:Вывод шаблона АДАС

@enduml ]]></ac:plain-text-body></ac:structured-macro>
<h3><ac:inline-comment-marker ac:ref="65d14856-dc0b-45db-b96d-26b1f5998538">Схема взаимодействия при удалении списка из Модуля списков, связанного с шаблоном АДАС.</ac:inline-comment-marker></h3><ac:structured-macro ac:name="plantuml" ac:schema-version="1" ac:macro-id="146cf727-603a-48e6-85b3-ef0dc1ed3030"><ac:parameter ac:name="atlassian-macro-output-type">INLINE</ac:parameter><ac:plain-text-body><![CDATA[@startuml
autonumber
skinparam ParticipantPadding 20
skinparam BoxPadding 20
skinparam maxmessagesize 200
skinparam shadowing false
autonumber

box "UI ARM.Front-end" #Lightblue 
actor "Analytic"
participant AFE as "ARM front-end"
activate Analytic
Analytic->AFE: Запрос на удаление списка
end box

participant BBPL as "bfp-bo-polocy-list"
activate AFE
AFE->NGINX:Вызов bfp-bo-policy-list https/rest/json
deactivate AFE
activate NGINX
NGINX->NGINX:Фильтр запроса
NGINX->BBPL:Маршрутизация к сервису bfp-bo-policy-list https/rest/json
deactivate NGINX
participant NGINX

box "ARM.Back-end" #Lightgreen
participant BBPL as "bfp-bo-policy-list"
database BOS as "back-office storage"
participant BBCAL as "bfp-bo-control-action-list"

activate BBPL
activate BOS
BBPL->BOS:Запрос удаления списка
BOS-->BBPL:Тех.квитанция
group **Ошибка.Остановка процесса**
BOS-->BBPL: Ошибка
BBPL-->NGINX: Ошибка
NGINX-->AFE: Ошибка
AFE-->Analytic:Сообщение об ошибке 
end 
deactivate BOS
end box
deactivate BBPL

activate BBPL
BBPL->BBCAL:Нотификация о удалении списка https/rest/json
BBCAL-->BBPL:Тех.квитанция


participant KF as "kafka"
participant BCCAL as "bfp-core-control-action-list"
BBCAL->KF:Публикация изменений по шаблону АДАС
BCCAL->KF:Вычитка изменений по шаблону АДАС


box "Antifraud Core" #Lightyellow
participant BCCAL as "bfp-bo-control-action-list"
end box

BBPL-->Analytic:Список удален 

@enduml]]></ac:plain-text-body></ac:structured-macro>
<h3><ac:inline-comment-marker ac:ref="09bcb897-dc71-4976-877d-019bc0087dc6">Схема взаимодействия при удалении правила из Модуля правил, связанного с шаблоном АДАС.</ac:inline-comment-marker></h3><ac:structured-macro ac:name="plantuml" ac:schema-version="1" ac:macro-id="08d043a6-915a-4329-b09b-66c3fa0ffa47"><ac:parameter ac:name="atlassian-macro-output-type">INLINE</ac:parameter><ac:plain-text-body><![CDATA[@startuml
autonumber
skinparam ParticipantPadding 20
skinparam BoxPadding 20
skinparam maxmessagesize 200
skinparam shadowing false
autonumber

box "UI ARM.Front-end" #Lightblue 
actor "Analytic"
participant AFE as "ARM front-end"
activate Analytic
Analytic->AFE: Запрос на удаление правила
end box

participant BBPR as "bfp-bo-polocy-rule"
activate AFE
AFE->NGINX:Вызов bfp-bo-policy-list https/rest/json
deactivate AFE
activate NGINX
NGINX->NGINX:Фильтр запроса
NGINX->BBPR:Маршрутизация к сервису bfp-bo-policy-rule https/rest/json
deactivate NGINX
participant NGINX

box "ARM.Back-end" #Lightgreen
participant BBPR as "bfp-bo-policy-rule"
database BOS as "back-office storage"
participant BBCAL as "bfp-bo-control-action-list"

activate BBPR
activate BOS
BBPR->BOS:Запрос удаления правила
BOS-->BBPR:Тех.квитанция
group **Ошибка.Остановка процесса**
BOS-->BBPR: Ошибка
BBPR-->NGINX: Ошибка
NGINX-->AFE: Ошибка
AFE-->Analytic:Сообщение об ошибке 
end 
deactivate BOS
end box
deactivate BBPR

activate BBPR
BBPR->BBCAL:Нотификация о удалении правила https/rest/json
BBCAL-->BBPR:Тех.квитанция

participant KF as "kafka"
participant BCCAL as "bfp-core-control-action-list"
BBCAL->KF:Публикация изменений по шаблону АДАС
BCCAL->KF:Вычитка изменений по шаблону АДАС


box "Antifraud Core" #Lightyellow
participant BCCAL as "bfp-bo-control-action-list"
end box

BBPR-->Analytic:Правило удалено 

@enduml
@enduml]]></ac:plain-text-body></ac:structured-macro>
<h1>Функциональные требования&nbsp;</h1>
<h2 style="text-decoration: none;">Требования к формату хранения</h2>
<p>Необходимо добавить таблицы:</p>
<ul>
<li>list_template;</li>
<li>list_template_to_list;</li>
<li>list_template_to_rule.</li></ul>
<h3>Таблица list<strong>_template - для хранения данных по шаблонам АДАС</strong></h3>
<table class="wrapped"><colgroup><col style="width: 38.0px;" /><col style="width: 190.0px;" /><col style="width: 102.0px;" /><col style="width: 224.0px;" /></colgroup>
<thead>
<tr>
<th class="numberingColumn" style="text-align: left;">№</th>
<th style="text-align: left;">
<p>Наименование атрибута</p></th>
<th style="text-align: left;">
<p>Тип данных</p></th>
<th style="text-align: left;">
<p>Описание атрибута</p></th></tr></thead>
<tbody>
<tr>
<td class="numberingColumn" style="text-align: left;">1</td>
<td style="text-align: left;">id</td>
<td style="text-align: left;">uuid</td>
<td style="text-align: left;"><span style="color: rgb(23,43,77);">Идентификатор шаблона АДАС</span></td></tr>
<tr>
<td class="numberingColumn" style="text-align: left;">2</td>
<td style="text-align: left;">name</td>
<td style="text-align: left;">varchar(200)</td>
<td style="text-align: left;">Наименование шаблона АДАС</td></tr>
<tr>
<td class="numberingColumn" style="text-align: left;">3</td>
<td style="text-align: left;">description</td>
<td style="text-align: left;">varchar(200)</td>
<td style="text-align: left;">Описание</td></tr>
<tr>
<td class="numberingColumn">4</td>
<td colspan="1">action</td>
<td colspan="1">varchar(15)</td>
<td colspan="1">Действие (добавить/удалить) с элементами списка</td></tr>
<tr>
<td class="numberingColumn">5</td>
<td colspan="1">attributeTTL</td>
<td colspan="1">int</td>
<td colspan="1">Время жизни значения атрибута в списке (в минутах)</td></tr>
<tr>
<td class="numberingColumn">6</td>
<td colspan="1">ttlShift</td>
<td colspan="1">int</td>
<td colspan="1"><span style="color: rgb(0,51,102);">Смещение старта времени жизни значения атрибута в списке (в минутах)</span></td></tr></tbody></table>
<h3>Таблица&nbsp;list<strong>_template</strong><strong>_to_list - для хранения связи списка с шаблонами АДАС</strong></h3>
<table class="wrapped"><colgroup><col /><col /><col /><col /></colgroup>
<tbody>
<tr>
<th class="numberingColumn">№</th>
<th>Наименование атрибута</th>
<th>Тип данных</th>
<th>Описание атрибута</th></tr>
<tr>
<td class="numberingColumn">1</td>
<td>list_template_id</td>
<td>uuid</td>
<td><span style="color: rgb(23,43,77);">Идентификатор шаблона АДАС</span></td></tr>
<tr>
<td class="numberingColumn">2</td>
<td>list_id</td>
<td>uuid</td>
<td><span style="color: rgb(23,43,77);">Идентификатор списка</span></td></tr></tbody></table>
<h3>Таблица&nbsp;list<strong>_template</strong><strong>_to</strong><strong>_rule - для хранения связи правил с шаблонами АДАС</strong></h3>
<table class="wrapped"><colgroup><col /><col /><col /><col /></colgroup>
<tbody>
<tr>
<th>№</th>
<th>Наименование атрибута</th>
<th>Тип данных</th>
<th>Описание атрибута</th></tr>
<tr>
<td>1</td>
<td>list_template_id</td>
<td>uuid</td>
<td><span style="color: rgb(23,43,77);">Идентификатор шаблона АДАС</span></td></tr>
<tr>
<td>2</td>
<td>rule_id</td>
<td>uuid</td>
<td><span style="color: rgb(23,43,77);">Идентификатор правила</span></td></tr></tbody></table>
<p><ac:structured-macro ac:name="drawio" ac:schema-version="1" ac:macro-id="201fcbb1-59fa-4937-812e-478c81c2aaca"><ac:parameter ac:name="border">true</ac:parameter><ac:parameter ac:name="diagramName">er ADAS</ac:parameter><ac:parameter ac:name="simpleViewer">false</ac:parameter><ac:parameter ac:name="links">auto</ac:parameter><ac:parameter ac:name="tbstyle">top</ac:parameter><ac:parameter ac:name="lbox">true</ac:parameter><ac:parameter ac:name="diagramWidth">431</ac:parameter><ac:parameter ac:name="revision">4</ac:parameter></ac:structured-macro></p>
<p><ac:placeholder>ER-диаграмма</ac:placeholder></p>
<h2>UI/UX</h2>
<h3>Карточка шаблона АДАС</h3>
<p><ac:image ac:width="600"><ri:attachment ri:filename="image2022-10-12_14-40-9.png" /></ac:image></p>
<h3>Журнал шаблонов АДАС</h3>
<p><ac:image ac:width="600"><ri:attachment ri:filename="image2022-10-12_14-58-11.png" /></ac:image></p>
<p><ac:placeholder>Инфа что будет отображаться на дорабатываемых/изменяемых страницах</ac:placeholder></p>
<h2>Требования к <ac:inline-comment-marker ac:ref="eeb5e298-055a-4d09-aec3-391d0a4ce030">программным</ac:inline-comment-marker>&nbsp;<ac:inline-comment-marker ac:ref="971ca08d-1abc-4afe-b88f-d63a0670e447">интерфейсам</ac:inline-comment-marker></h2><ac:structured-macro ac:name="expand" ac:schema-version="1" ac:macro-id="7c92e161-35ce-4019-b51a-815d80ea26a5"><ac:parameter ac:name="title">Open API</ac:parameter><ac:rich-text-body><ac:structured-macro ac:name="open-api" ac:schema-version="1" ac:macro-id="2dd2e8f0-7dbc-40d8-81e9-ebe839b0d593"><ac:plain-text-body><![CDATA[{
  "openapi": "3.0.1",
  "info": {
    "title": "Control actions list AP",
    "description": "API reference for developers",
    "version": "1.0"
  },
  "servers": [
    {
      "url": "http://localhost:8083/user"
    }
  ],
  "security": [
    {
      "JWT": [
        "read",
        "write"
      ]
    }
  ],
  "tags": [
    {
      "name": "External API",
      "description": "Внешний контролер Управляющие воздействия. Удаление и добавление значения атрибутов транзакции в списки"
    },
    {
      "name": "Internal API",
      "description": "Внутренний вспомогательный контролер Управляющие воздействия. Функционал по работе со связями. Удаление связей с правилами и списками"
    },
    {
      "name": "Integration API",
      "description": "API для взаимодействия со сервисами ядра"
    }
  ],
  "paths": {
    "/external/v1/action/control/list": {
      "post": {
        "tags": [
          "External API"
        ],
        "summary": "Создать УВ",
        "operationId": "actionListEControllerCreate",
        "requestBody": {
          "content": {
            "application/json": {
              "schema": {
                "$ref": "#/components/schemas/ControlActonListDto"
              }
            }
          },
          "required": true
        },
        "responses": {
          "200": {
            "description": "OK",
            "content": {
              "application/json": {
                "schema": {
                  "$ref": "#/components/schemas/ControlActonListDto"
                }
              }
            }
          }
        }
      }
    },
    "/external/v1/action/control/list/{id}": {
      "get": {
        "tags": [
          "External API"
        ],
        "summary": "Поиск УВ по уникальному ключу",
        "description": "Поиск УВ по кникальному ключу",
        "operationId": "actionListEControllerGetById",
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "required": true,
            "schema": {
              "type": "string",
              "format": "uuid"
            }
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "content": {
              "application/json": {
                "schema": {
                  "$ref": "#/components/schemas/ControlActonListDto"
                }
              }
            }
          }
        }
      },
      "delete": {
        "tags": [
          "External API"
        ],
        "summary": "Удалить УВ",
        "operationId": "actionListEControllerDelete",
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "required": true,
            "schema": {
              "type": "string",
              "format": "uuid"
            }
          }
        ],
        "responses": {
          "200": {
            "description": "OK"
          }
        }
      },
      "patch": {
        "tags": [
          "External API"
        ],
        "summary": "Обновить УВ",
        "operationId": "actionListEControllerSave",
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "required": true,
            "schema": {
              "type": "string",
              "format": "uuid"
            }
          }
        ],
        "requestBody": {
          "content": {
            "application/json": {
              "schema": {
                "$ref": "#/components/schemas/ControlActonListDto"
              }
            }
          },
          "required": true
        },
        "responses": {
          "200": {
            "description": "OK",
            "content": {
              "application/json": {
                "schema": {
                  "$ref": "#/components/schemas/ControlActonListDto"
                }
              }
            }
          }
        }
      }
    },
    "/integration/v1/state": {
      "get": {
        "tags": [
          "Integration API"
        ],
        "summary": "Отображение данных шаблонов УВ",
        "operationId": "actionListIntegraionControllerGetAll",
        "responses": {
          "200": {
            "description": "OK",
            "content": {
              "*/*": {
                "schema": {
                  "type": "object",
                  "additionalProperties": {
                    "$ref": "#/components/schemas/ListSettingsMetadata"
                  }
                }
              }
            }
          }
        }
      }
    },
    "/external/v1/action/control/list/{id}/rule/canAll": {
      "get": {
        "tags": [
          "External API"
        ],
        "summary": "Пагинированный поиск правил, доступных для привязки (нет связи с шаблоном)",
        "operationId": "actionListEControllerGetRuleWithoutRelation",
        "parameters": [
          {
            "name": "page",
            "in": "query",
            "description": "Zero-based page index (0..N)",
            "schema": {
              "type": "integer",
              "default": 0
            }
          },
          {
            "name": "size",
            "in": "query",
            "description": "The size of the page to be returned",
            "schema": {
              "type": "integer",
              "default": 20
            }
          },
          {
            "name": "sort",
            "in": "query",
            "description": "Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported.",
            "schema": {
              "type": "array",
              "items": {
                "type": "string"
              }
            }
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "content": {
              "*/*": {
                "schema": {
                  "$ref": "#/components/schemas/PagePolicyRuleMainInfoDto"
                }
              }
            }
          }
        }
      }
    },
    "/external/v1/action/control/list/all": {
      "get": {
        "tags": [
          "External API"
        ],
        "summary": "Вернуть весь список УВ",
        "operationId": "actionListEControllerFindAll",
        "parameters": [
          {
            "name": "page",
            "in": "query",
            "description": "Zero-based page index (0..N)",
            "schema": {
              "type": "integer",
              "default": 0
            }
          },
          {
            "name": "size",
            "in": "query",
            "description": "The size of the page to be returned",
            "schema": {
              "type": "integer",
              "default": 20
            }
          },
          {
            "name": "sort",
            "in": "query",
            "description": "Sorting criteria in the format: property(,asc|desc). Default sort order is ascending. Multiple sort criteria are supported.",
            "schema": {
              "type": "array",
              "items": {
                "type": "string"
              }
            }
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "content": {
              "application/json": {
                "schema": {
                  "$ref": "#/components/schemas/PageControlActonListDto"
                }
              }
            }
          }
        }
      }
    },
    "/internal/v1/action/control/list/relation/rule/{id}": {
      "delete": {
        "tags": [
          "Internal API"
        ],
        "summary": "Удалить связь у шаблона с правилом",
        "operationId": "actionListRelationIControllerDeleteRuleId",
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "description": "Уникальный идентификатор правила",
            "required": true,
            "schema": {
              "type": "string",
              "format": "uuid"
            }
          }
        ],
        "responses": {
          "200": {
            "description": "OK"
          }
        }
      }
    },
    "/internal/v1/action/control/list/relation/list/{id}": {
      "delete": {
        "tags": [
          "Internal API"
        ],
        "summary": "Удалить связь у шаблона с листом",
        "operationId": "actionListRelationIControllerDeleteListId",
        "parameters": [
          {
            "name": "id",
            "in": "path",
            "description": "Уникальный идентификатор списка",
            "required": true,
            "schema": {
              "type": "string",
              "format": "uuid"
            }
          }
        ],
        "responses": {
          "200": {
            "description": "OK"
          }
        }
      }
    }
  },
  "components": {
    "schemas": {
      "ControlActonListDto": {
        "required": [
          "action",
          "attributeTTL",
          "id",
          "listIds",
          "name",
          "ruleIds",
          "ttlShift"
        ],
        "type": "object",
        "properties": {
          "id": {
            "type": "string",
            "description": "Уникальный идентификатор сущности",
            "format": "uuid",
            "readOnly": true,
            "example": "1dc50b7a-edf7-4e34-b4c3-de70de97ae63"
          },
          "name": {
            "type": "string",
            "description": "Наименование шаблона АДАС",
            "example": "Шаблон по удалению номера"
          },
          "description": {
            "type": "string",
            "description": "Подробное описание шаблона",
            "example": "Шаблон удаляет номера согласно привязанному правилу"
          },
          "action": {
            "type": "string",
            "description": "Действие (добавить/удалить) с элементами списка",
            "example": "DELETE",
            "enum": [
              "ADD",
              "DELETE"
            ]
          },
          "attributeTTL": {
            "type": "integer",
            "description": "Время жизни значения атрибута в списке (в минутах)",
            "format": "int32",
            "example": 5
          },
          "ttlShift": {
            "type": "integer",
            "description": "Смещение старта времени жизни значения атрибута в списке (в минутах)",
            "format": "int32",
            "example": 15
          },
          "ruleIds": {
            "uniqueItems": true,
            "type": "array",
            "description": "Идентификатор списка",
            "example": [
              "dd78d100-baf8-4e6b-8b1c-84853755bf46",
              "5ac7e13f-aa36-4059-833d-c0a79267a895"
            ],
            "items": {
              "type": "string",
              "description": "Идентификатор списка",
              "format": "uuid"
            }
          },
          "lists": {
            "uniqueItems": true,
            "type": "array",
            "description": "Идентификатор правила",
            "items": {
              "$ref": "#/components/schemas/ListItemPayload"
            }
          }
        },
        "description": "Модель АДАС"
      },
      "PageControlActonListDto": {
        "type": "object",
        "properties": {
          "totalElements": {
            "type": "integer",
            "format": "int64"
          },
          "totalPages": {
            "type": "integer",
            "format": "int32"
          },
          "number": {
            "type": "integer",
            "format": "int32"
          },
          "size": {
            "type": "integer",
            "format": "int32"
          },
          "content": {
            "type": "array",
            "items": {
              "$ref": "#/components/schemas/ControlActonListDto"
            }
          },
          "first": {
            "type": "boolean"
          },
          "last": {
            "type": "boolean"
          },
          "numberOfElements": {
            "type": "integer",
            "format": "int32"
          },
          "sort": {
            "$ref": "#/components/schemas/Sort"
          },
          "pageable": {
            "$ref": "#/components/schemas/PageableObject"
          },
          "empty": {
            "type": "boolean"
          }
        }
      },
      "PagePolicyRuleMainInfoDto": {
        "type": "object",
        "properties": {
          "totalElements": {
            "type": "integer",
            "format": "int64"
          },
          "totalPages": {
            "type": "integer",
            "format": "int32"
          },
          "number": {
            "type": "integer",
            "format": "int32"
          },
          "size": {
            "type": "integer",
            "format": "int32"
          },
          "content": {
            "type": "array",
            "items": {
              "$ref": "#/components/schemas/PolicyRuleMainInfoDto"
            }
          },
          "first": {
            "type": "boolean"
          },
          "last": {
            "type": "boolean"
          },
          "numberOfElements": {
            "type": "integer",
            "format": "int32"
          },
          "sort": {
            "$ref": "#/components/schemas/Sort"
          },
          "pageable": {
            "$ref": "#/components/schemas/PageableObject"
          },
          "empty": {
            "type": "boolean"
          }
        }
      },
      "PageableObject": {
        "type": "object",
        "properties": {
          "offset": {
            "type": "integer",
            "format": "int64"
          },
          "sort": {
            "$ref": "#/components/schemas/Sort"
          },
          "pageSize": {
            "type": "integer",
            "format": "int32"
          },
          "pageNumber": {
            "type": "integer",
            "format": "int32"
          },
          "unpaged": {
            "type": "boolean"
          },
          "paged": {
            "type": "boolean"
          }
        }
      },
      "ListSettingsMetadata": {
        "type": "object",
        "properties": {
          "id": {
            "type": "string",
            "format": "uuid",
            "description": "Идентификатор связанного шаблона АДАС."
          },
          "action": {
            "type": "string",
            "description": "Действие, которое необходимо выполнить с атрибутом транзакции (вставить или удалить из списка).",
            "enum": [
              "ADD",
              "DELETE"
            ]
          },
          "attributeTTL": {
            "description": "Время жизни значения атрибута в списке (в минутах).",
            "type": "integer"
          },
          "ttlShift": {
            "description": "Смещение старта времени жизни значения атрибута в списке (в минутах).",
            "type": "integer"
          },
          "lists": {
            "description": "Списки, в которые нужно вставить или удалить атрибут транзакции.",
            "type": "array",
            "items": {
              "$ref": "#/components/schemas/ListItemPayload"
            }
          }
        }
      },
      "ListItemPayload": {
        "type": "object",
        "properties": {
          "id": {
            "type": "string",
            "format": "uuid",
            "description": "Идентификатор списков."
          },
          "attributeName": {
            "type": "string",
            "description": "Название атрибута в транзакции, на основе которого создан список."
          }
        }
      },
      "PolicyRuleMainInfoDto": {
        "type": "object",
        "properties": {
          "id": {
            "type": "string",
            "format": "uuid"
          },
          "name": {
            "type": "string"
          },
          "action": {
            "type": "string",
            "enum": [
              "ALLOW",
              "CHALLENGE",
              "DENY",
              "REVIEW"
            ]
          },
          "state": {
            "type": "string",
            "enum": [
              "PRODUCTION",
              "SUSPENDED",
              "TEST",
              "WORK_IN_PROGRESS"
            ]
          },
          "updated": {
            "type": "string",
            "format": "date-time"
          }
        }
      },
      "Sort": {
        "type": "object",
        "properties": {
          "empty": {
            "type": "boolean"
          },
          "sorted": {
            "type": "boolean"
          },
          "unsorted": {
            "type": "boolean"
          }
        }
      }
    },
    "securitySchemes": {
      "JWT": {
        "type": "http",
        "scheme": "bearer",
        "bearerFormat": "JWT"
      }
    }
  }
}]]></ac:plain-text-body></ac:structured-macro></ac:rich-text-body></ac:structured-macro>
<h3>Интеграция <ac:inline-comment-marker ac:ref="919689ce-2746-4d80-8311-58990eae9b7f">АРМ с ядром</ac:inline-comment-marker></h3>
<p>Для интеграции сервиса АРМ <strong>bo-control-action-list</strong> с сервисом ядра&nbsp;<strong><ac:inline-comment-marker ac:ref="09d2a16a-1202-4753-9d5a-0bcbabba7765">core-<strong>control-action-list</strong></ac:inline-comment-marker></strong>&nbsp;используем <ac:inline-comment-marker ac:ref="a3744f86-bfee-42ab-8a94-4e8ff3e0e1ef">Kafka</ac:inline-comment-marker>,&nbsp;<span style="color: rgb(23,43,77);">где ключом будет id шаблона.</span></p>
<p>Для передачи данных используются <ac:inline-comment-marker ac:ref="07c63379-0b83-400c-ac43-795de0102286">команды</ac:inline-comment-marker>&nbsp;(<span style="color: rgb(23,43,77);">передача данных в топик&nbsp;</span><span style="color: rgb(0,51,102);"><strong>UPDATE_TEMPLATE</strong></span><span style="color: rgb(23,43,77);">&nbsp;):</span></p>
<p><span style="color: rgb(0,0,0);"><span style="color: black;">kind=update&nbsp;</span></span></p>
<p><span style="color: rgb(0,0,0);"><span style="color: black;">kind=delete</span></span></p>
<h3><span style="color: rgb(0,0,0);"><span style="color: black;">В каких случаях передается команда <ac:inline-comment-marker ac:ref="32203f2b-1cdf-4465-b833-abc75bbcf7bf">UPDATE</ac:inline-comment-marker></span></span></h3>
<ul>
<li><span style="color: rgb(0,0,0);"><span style="color: black;">При привязки правила к шаблону в карточке шаблона АДАС в разделе Использование в правилах</span></span></li>
<li><span style="color: rgb(0,0,0);"><span style="color: black;">При <ac:inline-comment-marker ac:ref="16d28ef4-72e7-4bae-93df-84b6cbd73e84">обновлении</ac:inline-comment-marker> шаблона привязанного правилу:</span></span>
<ul>
<li>В разделе <strong>Параметры</strong>&nbsp;
<ul>
<li>изменение параметра Действие (<span style="color: rgb(23,43,77);">action</span>)</li>
<li>изменение параметра&nbsp;<span style="color: rgb(23,43,77);">Время жизни атрибута в списке (в минутах) (attributeTTL)</span></li>
<li><span style="color: rgb(23,43,77);">изменение параметра&nbsp;<span style="color: rgb(0,51,102);">Смещение старта времени жизни атрибута в списке (в минутах) (ttlShift)</span></span></li></ul></li>
<li><span style="color: rgb(23,43,77);"><span style="color: rgb(0,51,102);">В разделе <strong>Списки</strong></span></span>
<ul>
<li><span style="color: rgb(0,0,0);"><span style="color: black;">ручное редактирование содержимого в карточке шаблона</span></span></li>
<li><span style="color: rgb(0,0,0);"><span style="color: black;">автоматическое, при удалении списка из модуля Списков</span></span></li></ul></li></ul></li></ul>
<h3><span style="color: rgb(0,0,0);"><span style="color: black;"><ac:inline-comment-marker ac:ref="412f4753-390d-47f7-b34d-07c67ca59724">В каких случаях передается команда DELETE</ac:inline-comment-marker></span></span></h3>
<ul>
<li><span style="color: rgb(0,0,0);"><span style="color: black;"><ac:inline-comment-marker ac:ref="f84b8440-a9e6-466d-9a3a-c1ef04364c79">При</ac:inline-comment-marker> <ac:inline-comment-marker ac:ref="24f6c14e-dfeb-4aa9-8289-5f33b6db828d">отвязки</ac:inline-comment-marker> шаблона от правила</span></span>
<ul>
<li><span style="color: rgb(23,43,77);"><span style="color: rgb(0,51,102);">В разделе <strong>Использование в правила</strong></span></span>
<ul>
<li><span style="color: rgb(0,0,0);"><span style="color: black;">ручное редактирование в карточке шаблона</span></span></li>
<li><span style="color: rgb(0,0,0);"><span style="color: black;">автоматическое, при удалении правила в модуле Правил</span></span></li></ul></li></ul></li></ul>
<ul>
<li><span style="color: rgb(0,0,0);"><span style="color: black;"><span style="color: rgb(23,43,77);">При удаление шаблона привязанного к правилу</span></span></span></li></ul>
<p><span style="color: rgb(0,0,0);"><ac:inline-comment-marker ac:ref="7edb45f7-a667-417b-99d8-bd5a281ea96b">Структура</ac:inline-comment-marker> сообщения в топике<span>&nbsp;UPDATE_TEMPLATE</span><span style="color: black;">&nbsp;kind=update</span>.</span></p>
<table class="wrapped"><colgroup><col style="width: 38.0px;" /><col style="width: 180.0px;" /><col style="width: 203.0px;" /><col style="width: 77.0px;" /><col style="width: 357.0px;" /><col style="width: 119.0px;" /></colgroup>
<thead>
<tr>
<th style="text-align: left;">
<p>№</p></th>
<th style="text-align: left;">
<p>Элемент JSON главный</p></th>
<th colspan="1" style="text-align: left;">
<p>Элемент JSON вложенный</p></th>
<th style="text-align: left;">
<p>JVM тип</p></th>
<th style="text-align: left;">
<p>Описание</p></th>
<th style="text-align: left;">
<p>kind=update</p></th></tr></thead>
<tbody>
<tr>
<td colspan="1" style="text-align: left;">1</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">kind</span></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">String</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(23,43,77);">Тип обработки сообщения (создать/<ac:inline-comment-marker ac:ref="33590aa4-69b0-444a-9b95-e49f6005110e">обновить</ac:inline-comment-marker> -<span>&nbsp;</span><span style="color: rgb(0,0,0);"><span style="color: black;">update</span></span>)</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">2</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">ruleId</span></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">UUID</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">Идентификатор правила</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">3</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">template</span></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">4</td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">id</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">UUID</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">Идентификатор шаблона</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1">5</td>
<td colspan="1"><br /></td>
<td colspan="1">lists</td>
<td colspan="1"><span style="color: rgb(0,0,0);">String</span></td>
<td colspan="1">Списки с id списков в которых необходимо обновить содержимое + наименование атрибутов (attibuteName)</td>
<td colspan="1"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">6</td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">action</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">String</span></td>
<td colspan="1" style="text-align: left;">Действие (<ac:inline-comment-marker ac:ref="ef0c1036-abc5-4691-b9db-e84846cb60f1">добавить (ADD) /удалить (DELETE)</ac:inline-comment-marker>) с элементами списка</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">7</td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;">attributeTTL</td>
<td colspan="1" style="text-align: left;">Int</td>
<td colspan="1" style="text-align: left;">Время жизни значения атрибута в списке (в минутах)</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">необязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">8</td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;">ttlShift</td>
<td colspan="1" style="text-align: left;">Int</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,51,102);">Смещение старта времени жизни значения атрибута в списке (в минутах)</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">необязательно</span></td></tr></tbody></table>
<p><span style="color: rgb(0,0,0);">Структура сообщения в топике<span>&nbsp;UPDATE_TEMPLATE</span><span style="color: black;">&nbsp;</span><span style="color: black;">kind=delete</span>.</span></p>
<table class="wrapped"><colgroup><col style="width: 38.0px;" /><col style="width: 180.0px;" /><col style="width: 203.0px;" /><col style="width: 77.0px;" /><col style="width: 357.0px;" /><col style="width: 119.0px;" /></colgroup>
<thead>
<tr>
<th style="text-align: left;">
<p>№</p></th>
<th style="text-align: left;">
<p>Элемент JSON главный</p></th>
<th colspan="1" style="text-align: left;">
<p>Элемент JSON вложенный</p></th>
<th style="text-align: left;">
<p>JVM тип</p></th>
<th style="text-align: left;">
<p>Описание</p></th>
<th style="text-align: left;">
<p>kind=delete</p></th></tr></thead>
<tbody>
<tr>
<td colspan="1" style="text-align: left;">1</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">kind</span></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">String</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(23,43,77);">Тип обработки сообщения (удалить -<span>&nbsp;</span><span style="color: rgb(0,0,0);"><span style="color: black;">delete</span></span>)</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">2</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">ruleId</span></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">UUID</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">Идентификатор правила</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr>
<tr>
<td colspan="1" style="text-align: left;">3</td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">templateId</span></td>
<td colspan="1" style="text-align: left;"><br /></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">UUID</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">Идентификатор шаблона</span></td>
<td colspan="1" style="text-align: left;"><span style="color: rgb(0,0,0);">обязательно</span></td></tr></tbody></table>
<p><strong><ac:inline-comment-marker ac:ref="da1ef8b5-609d-4979-956a-2fec26e2902c">Пример команд</ac:inline-comment-marker>:</strong></p><ac:structured-macro ac:name="code" ac:schema-version="1" ac:macro-id="89a72b40-fd0c-47ec-a513-6ab96206146d"><ac:parameter ac:name="language">yml</ac:parameter><ac:parameter ac:name="theme">Emacs</ac:parameter><ac:parameter ac:name="firstline">1</ac:parameter><ac:parameter ac:name="linenumbers">true</ac:parameter><ac:plain-text-body><![CDATA[// обновление информации по шаблону, привязка к правилу
{
  "kind": "update",
  "ruleId": "efb3fd24-ddd5-47c2-be58-68b725936ddb",
  "template": {
    "id": "7f12ac1f-3d21-4491-899c-e3789b427dc5",
    "lists": [
       {"id": "07d74672-e8fb-49f3-ba79-41a5fd707c6b",
        "attributeName": "Канал"
       },
       {"id": "f0aae6ab-1514-41fd-bdbd-cf55fd0cc143",
        "attributeName": "Сумма платежа"
       }
     ]
    "action": "ADD",
    "attributeTTL": "120",
    "ttlShift": "0"
  }
}

// отвязка от правила
{
  "kind": "delete",
  "ruleId": "efb3fd24-ddd5-47c2-be58-68b725936ddb",
  "templateId": "7f12ac1f-3d21-4491-899c-e3789b427dc5"
}]]></ac:plain-text-body></ac:structured-macro>
<p><br /></p>
<p class="with-breadcrumbs">control-action-list-kafka-spec</p><ac:structured-macro ac:name="code" ac:schema-version="1" ac:macro-id="51cd04e0-cd6c-4a84-b2ec-6865d4220204"><ac:parameter ac:name="language">yml</ac:parameter><ac:parameter ac:name="theme">Emacs</ac:parameter><ac:parameter ac:name="firstline">1</ac:parameter><ac:parameter ac:name="linenumbers">true</ac:parameter><ac:plain-text-body><![CDATA[{
  "asyncapi": "2.4.0",
  "info": {
    "title": "Сервис АДАС",
    "version": "1.0.0"
  },
  "channels": {
    "ROSTER-ELEMENT-UPDATES": {
      "description": "Топик, который принимает сообщения на вставку элементов списков в игнайт.",
      "publish": {
        "message": {
          "oneOf": [
            {
              "$ref": "#/components/messages/updateRosterElementCommand"
            },
            {
              "$ref": "#/components/messages/deleteRosterElementCommand"
            }
          ]
        }
      }
    },
    "ITEMS_UPDATE_BO": {
      "description": "Топик, который принимает сообщения на вставку элементов списков в сервис списков в бек-офисе.",
      "publish": {
        "message": {
          "oneOf": [
            {
              "$ref": "#/components/messages/updateRosterElementCommand"
            },
            {
              "$ref": "#/components/messages/deleteRosterElementCommand"
            }
          ]
        }
      }
    },
    "UPDATE_TEMPLATE": {
      "description": "Топик, который принимает команды по урпавлению шаблонами АДАС",
      "publish": {
        "message": {
          "oneOf": [
            {
              "$ref": "#/components/messages/updateListSettingsCommand"
            },
            {
              "$ref": "#/components/messages/deleteListSettingsCommand"
            }
          ]
        }
      }
    }
  },
  "components": {
    "messages": {
      "updateRosterElementCommand": {
        "name": "updateRosterElementCommand",
        "title": "updateRosterElementCommand",
        "summary": "Добавляет элемент в список. Если списка не существует, то создает его.",
        "contentType": "application/json",
        "payload": {
          "$ref": "#/components/schemas/updateRoserElementCommandPayload"
        }
      },
      "deleteRosterElementCommand": {
        "name": "deleteRosterElementCommand",
        "title": "deleteRosterElementCommand",
        "summary": "Удаляет элемент списка.",
        "contentType": "application/json",
        "payload": {
          "$ref": "#/components/schemas/deleteRosterElementCommandPayload"
        }
      },
      "updateListSettingsCommand": {
        "name": "updateListSettingsCommand",
        "title": "updateListSettingsCommand",
        "contentType": "application/json",
        "payload": {
          "$ref": "#/components/schemas/updateListSettingsCommandPayload"
        }
      },
      "deleteListSettingsCommand": {
        "name": "deleteListSettingCommand",
        "title": "deleteListSettingCommand",
        "contentType": "application/json",
        "payload": {
          "$ref": "#/components/schemas/deleteListSettingsCommandPayload"
        }
      }
    },
    "schemas": {
      "updateRoserElementCommandPayload": {
        "type": "object",
        "properties": {
          "kind": {
            "type": "string",
            "description": "Тип команды",
            "enum": [
              "update-element"
            ]
          },
          "rosterId": {
            "type": "string",
            "format": "uuid",
            "description": "Id списка."
          },
          "start": {
            "type": "string",
            "format": "date-time",
            "description": "Временная метка, с которой действует элемента списка. Например, если нужно проверять вхождение в список с какого-то определенного момента времени."
          },
          "end": {
            "type": "string",
            "format": "date-time",
            "description": "Временная метка, с которой элемент списка перестает действовать."
          },
          "value": {
            "type": "object",
            "description": "Значение элемента."
          }
        }
      },
      "deleteRosterElementCommandPayload": {
        "type": "object",
        "properties": {
          "kind": {
            "type": "string",
            "description": "Тип команды.",
            "enum": [
              "delete-element"
            ]
          },
          "rosterId": {
            "type": "string",
            "format": "uuid",
            "description": "Id списка."
          },
          "value": {
            "type": "object",
            "description": "Значение элемента."
          }
        }
      },
      "updateListSettingsCommandPayload": {
        "type": "object",
        "properties": {
          "kind": {
            "type": "string",
            "description": "Тип команды.",
            "enum": [
              "update"
            ]
          },
          "ruleId": {
            "type": "string",
            "format": "uuid",
            "description": "Идентификатор связанного правила."
          },
          "listSettingsMetadata": {
            "type": "object",
            "properties": {
              "id": {
                "type": "string",
                "format": "uuid",
                "description": "Идентификатор связанного шаблона АДАС."
              },
              "action": {
                "type": "string",
                "description": "Действие, которое необходимо выполнить с атрибутом транзакции (вставить или удалить из списка).",
                "enum": [
                  "add",
                  "delete"
                ]
              },
              "attributeTTL": {
                "description": "Время жизни значения атрибута в списке (в минутах).",
                "type": "integer"
              },
              "ttlShift": {
                "description": "Смещение старта времени жизни значения атрибута в списке (в минутах).",
                "type": "integer"
              },
              "lists": {
                "description": "Списки, в которые нужно вставить или удалить атрибут транзакции.",
                "type": "array",
                "items": {
                  "$ref": "#/components/schemas/listItemPayload"
                }
              }
            }
          }
        }
      },
      "deleteListSettingsCommandPayload": {
        "type": "object",
        "properties": {
          "kind": {
            "type": "string",
            "description": "Тип команды.",
            "enum": [
              "delete"
            ]
          },
          "ruleId": {
            "type": "string",
            "format": "uuid",
            "description": "Идентификатор связанного правила."
          },
          "listSettingsTempalteId": {
            "type": "string",
            "format": "uuid",
            "description": "Идентификатор связанного шаблона АДАС."
          }
        }
      },
      "listItemPayload": {
        "type": "object",
        "properties": {
          "id": {
            "type": "string",
            "format": "uuid",
            "description": "Идентификатор списков."
          },
          "attributeName": {
            "type": "string",
            "description": "Название атрибута в транзакции, на основе которого создан список."
          }
        }
      }
    }
  }
}]]></ac:plain-text-body></ac:structured-macro>
<h2 style="text-decoration: none;"><span style="color: rgb(51,51,51);">Требования безопасности</span></h2>
<p><span style="color: rgb(51,51,51);"><span style="color: rgb(0,0,0);text-decoration: none;">Требования безопасности описаны на страницах:&nbsp;</span><a href="https://confluence.sberbank.ru/pages/viewpage.action?pageId=7502398610" style="text-decoration: none;" rel="nofollow">Требования ИБ к OpenShift</a><span style="color: rgb(0,0,0);text-decoration: none;">,&nbsp;</span><a href="https://confluence.sberbank.ru/pages/viewpage.action?pageId=7502398623" style="text-decoration: none;" rel="nofollow">Требования ИБ к Kafka</a></span></p>
<p><span style="color: rgb(51,51,51);"><ac:placeholder>детальные требования от безы</ac:placeholder></span></p>
<h2 style="text-decoration: none;"><span style="color: rgb(51,51,51);">Аудит</span></h2>
<p>Система должна фиксировать действия в описанном ниже формате для дальнейшей сериализации в JSON и отправки в Кафку:</p>
<table class="wrapped">
<thead>
<tr>
<th style="text-align: left;"><br /></th>
<th style="text-align: left;">
<p>Название поля</p></th>
<th style="text-align: left;">
<p>Тип</p></th>
<th style="text-align: left;">
<p>Описание</p></th></tr></thead><colgroup><col style="width: 36.0px;" /><col style="width: 126.0px;" /><col style="width: 158.0px;" /><col style="width: 507.0px;" /></colgroup>
<tbody>
<tr>
<td style="text-align: left;">1</td>
<td style="text-align: left;">
<p>id</p></td>
<td style="text-align: left;">UUID</td>
<td style="text-align: left;"><span style="color: rgb(23,43,77);">Уникальный ключ фиксируемого действия</span><span style="color: rgb(23,43,77);">(события)</span></td></tr>
<tr>
<td style="text-align: left;">2</td>
<td style="text-align: left;">creationTime</td>
<td style="text-align: left;">Long</td>
<td style="text-align: left;">Дата и время действия - Timestamp - UTC+0 с точностью до милисекунды</td></tr>
<tr>
<td style="text-align: left;">3</td>
<td style="text-align: left;">userId</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">UUID пользователя</td></tr>
<tr>
<td style="text-align: left;">4</td>
<td style="text-align: left;">username</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">Логин пользователя</td></tr>
<tr>
<td style="text-align: left;">5</td>
<td style="text-align: left;">userFIO</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">ФИО пользователя (если есть)</td></tr>
<tr>
<td style="text-align: left;">6</td>
<td style="text-align: left;">auditObject</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">
<p>Тип объекта системы<span>&nbsp;</span><em>(если применимо)</em></p></td></tr>
<tr>
<td style="text-align: left;">7</td>
<td style="text-align: left;">auditAction</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">Действие (Перечень действий представлен ниже)</td></tr>
<tr>
<td style="text-align: left;">8</td>
<td style="text-align: left;">auditObjectId</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">
<p>ID объекта<span>&nbsp;</span><em>(если применимо)</em></p></td></tr>
<tr>
<td style="text-align: left;">9</td>
<td style="text-align: left;">before</td>
<td style="text-align: left;">Map&lt;String, Object&gt;</td>
<td style="text-align: left;">
<p>Предыдущие значения атрибутов/параметров<span>&nbsp;</span><em>(если применимо)</em></p></td></tr>
<tr>
<td style="text-align: left;">10</td>
<td style="text-align: left;">parameters</td>
<td style="text-align: left;">Map&lt;String, Object&gt;</td>
<td style="text-align: left;">
<p>Параметры действия / Новые значения атрибутов<span>&nbsp;</span><em>(если применимо)</em></p></td></tr>
<tr>
<td style="text-align: left;">11</td>
<td style="text-align: left;">comments</td>
<td style="text-align: left;">String</td>
<td style="text-align: left;">
<p>Комментарий<span>&nbsp;</span><em>(если применимо)</em></p></td></tr>
<tr>
<td style="text-align: left;">12</td>
<td style="text-align: left;">result</td>
<td style="text-align: left;">boolean</td>
<td style="text-align: left;">
<p>Результат<span>&nbsp;</span>действия<span>&nbsp;</span>(успех / неудача)</p></td></tr></tbody></table>
<p><strong>Объект&nbsp;CONTROL_ACTION_ADD_ATTRIBUTE (рабочее название, может отличаться от реализации)&nbsp;<span class="Y2IQFc" lang="en">Шаблонов&nbsp;</span>автоматического удаления или добавления значения атрибутов в списки</strong></p>
<table class="relative-table wrapped" style="width: 611.0px;">
<thead>
<tr>
<th style="text-align: left;">
<p>№</p></th>
<th style="text-align: left;">
<p>Тип объекта системы</p></th>
<th style="text-align: left;">
<p>Действие</p></th>
<th style="text-align: left;">
<p>ID объекта</p></th></tr></thead><colgroup><col style="width: 42.8438px;" /><col style="width: 253.266px;" /><col style="width: 168.547px;" /><col style="width: 145.344px;" /></colgroup>
<tbody>
<tr>
<td colspan="1" style="text-align: left;">1</td>
<td colspan="1" style="text-align: left;">CONTROL_ACTION_ADD_ATTRIBUTE</td>
<td colspan="1" style="text-align: left;">Просмотр журнала шаблонов</td>
<td colspan="1" style="text-align: left;"><br /></td></tr>
<tr>
<td style="text-align: left;">2</td>
<td style="text-align: left;">CONTROL_ACTION_ADD_ATTRIBUTE</td>
<td style="text-align: left;">Просмотр карточки шаблона</td>
<td style="text-align: left;">ID шаблона</td></tr>
<tr>
<td style="text-align: left;">3</td>
<td style="text-align: left;">CONTROL_ACTION_ADD_ATTRIBUTE</td>
<td style="text-align: left;">Редактирование шаблона</td>
<td style="text-align: left;">ID шаблона</td></tr>
<tr>
<td style="text-align: left;">4</td>
<td style="text-align: left;">CONTROL_ACTION_ADD_ATTRIBUTE</td>
<td style="text-align: left;">Добавление шаблона</td>
<td style="text-align: left;">В случае успеха &mdash; ID<span>&nbsp;шаблона</span></td></tr>
<tr>
<td style="text-align: left;">5</td>
<td style="text-align: left;">CONTROL_ACTION_ADD_ATTRIBUTE</td>
<td style="text-align: left;">Удаление шаблона</td>
<td style="text-align: left;"><span style="color: rgb(23,43,77);">ID шаблона</span></td></tr></tbody></table>
<p><span style="color: rgb(51,51,51);"><ac:placeholder>Указываем в каких точках аудит, что отдаем. Если ничего не меняется с предыдущей реализации, то явно указываем это &nbsp;</ac:placeholder></span></p></ac:rich-text-body></ac:structured-macro>