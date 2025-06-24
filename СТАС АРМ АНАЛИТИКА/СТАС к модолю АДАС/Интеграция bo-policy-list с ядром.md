<h1>История</h1>
<table class="wrapped"><colgroup><col /><col /><col /><col /></colgroup>
<tbody>
<tr>
<th class="numberingColumn">№</th>
<th>Дата</th>
<th>Изменения</th>
<th>Автор</th></tr>
<tr>
<td class="numberingColumn">1</td>
<td>
<div class="content-wrapper">
<p><time datetime="2022-12-28" />&nbsp;</p></div></td>
<td>Статья создана</td>
<td>
<div class="content-wrapper">
<p><ac:link><ri:user ri:userkey="8aa405e56e670730016e695c60670008" /></ac:link></p></div></td></tr></tbody></table>
<h1>Интеграция<span>&nbsp;</span>АРМ с ядром</h1>
<p>Для интеграции сервиса АРМ<span>&nbsp;</span><strong>bo-policy-list</strong><span>&nbsp;</span>с сервисом ядра&nbsp;<strong>core-policy-list</strong>&nbsp;используем Kafka.</p>
<p>Для передачи данных используются<span>&nbsp;</span>команды&nbsp;(<span style="color: rgb(23,43,77);">передача данных в топик&nbsp;</span><span style="color: rgb(0,51,102);"><strong>UPDATE_TEMPLATE</strong></span><span style="color: rgb(23,43,77);">&nbsp;):</span></p>
<p><span style="color: rgb(0,0,0);"><span style="color: black;">kind=update&nbsp;</span></span></p>
<p><span style="color: rgb(0,0,0);"><span style="color: black;">kind=delete</span></span></p>
<h2><span style="color: rgb(0,0,0);"><span style="color: black;">В каких случаях передается команда<span>&nbsp;</span>UPDATE</span></span></h2>
<table class="wrapped relative-table" style="width: 29.9465%;"><colgroup><col style="width: 4.2486%;" /><col style="width: 95.7276%;" /></colgroup>
<tbody>
<tr>
<th class="numberingColumn">
<p>№</p></th>
<th>
<p>Название</p></th></tr>
<tr>
<td class="numberingColumn">1</td>
<td>Топик ROSTER-FACT-UPDATES Команда Update Создание Активного Списка без элементов</td></tr>
<tr>
<td class="numberingColumn">2</td>
<td>Топик ROSTER-FACT-UPDATES команда Update Активация Списка без элементов</td></tr>
<tr>
<td class="numberingColumn">3</td>
<td>Топик ROSTER-ELEMENT-UPDATES Команда Update-element Добавление элементов в Активный Список без элементов</td></tr>
<tr>
<td class="numberingColumn">4</td>
<td>
<p>Топик ROSTER-ELEMENT-UPDATES Команда Update-element Добавление элементов в Неактивный Список без элементов</p></td></tr>
<tr>
<td class="numberingColumn">5</td>
<td>
<p>Топики ROSTER-FACT-UPDATES команда Update первая Активация Списка с элементами</p></td></tr>
<tr>
<td class="numberingColumn">6</td>
<td>
<p>Топики ROSTER-FACT-UPDATES команда Update Активация ранее Деактивированного Списка с элементами</p></td></tr>
<tr>
<td class="numberingColumn">7</td>
<td>
<p>Топик ROSTER-ELEMENT-UPDATES команда Update-element &nbsp;Изменение в элементе входящем в Активный список</p></td></tr>
<tr>
<td class="numberingColumn">8</td>
<td>
<p>Топик ROSTER-ELEMENT-UPDATES команда Update-element &nbsp;Изменение в элементе входящем в Неактивный список</p></td></tr></tbody></table>
<h2><span style="color: rgb(0,0,0);"><span style="color: black;">В каких случаях передается команда DELETE</span></span></h2>
<table class="wrapped relative-table" style="width: 29.9799%;"><colgroup><col style="width: 4.24386%;" /><col style="width: 95.7338%;" /></colgroup>
<tbody>
<tr>
<th class="numberingColumn">№</th>
<th>
<p>Название</p></th></tr>
<tr>
<td class="numberingColumn">1</td>
<td>Топик ROSTER-FACT-UPDATES команда Delete Деактивация Списка без элементов</td></tr>
<tr>
<td class="numberingColumn">2</td>
<td>Топик ROSTER-FACT-UPDATES команда Delete Удаление Активного Списка без элементов</td></tr>
<tr>
<td class="numberingColumn">3</td>
<td>
<p>Топик ROSTER-ELEMENT-UPDATES Команда Delete-element Удаление всех элементов в Активном Списке</p></td></tr>
<tr>
<td class="numberingColumn">4</td>
<td>
<p>Топик ROSTER-ELEMENT-UPDATES Команда Delete-element Удаление всех элементов в Неактивном Списке</p></td></tr>
<tr>
<td class="numberingColumn">5</td>
<td>
<p>Топики ROSTER-FACT-UPDATES команда Delete Деактивация Списка с элементами</p></td></tr>
<tr>
<td class="numberingColumn">6</td>
<td>
<p>Топики ROSTER-FACT-UPDATES и ROSTER-ELEMENT-UPDATES команда Delete Удаление Активного списка с элементами</p></td></tr>
<tr>
<td class="numberingColumn">7</td>
<td>
<p>Топик ROSTER-ELEMENT-UPDATES команда Delete Удаление Неактивного списка с элементами</p></td></tr></tbody></table>