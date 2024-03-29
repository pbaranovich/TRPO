|      USE CASE 1        | ПОЛЬЗОВАТЕЛЬ НАХОДИТ БЛОГ ПО НАЗВАНИЮ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Найти блог по названию |
| **Предусловие**        | Пользователь зашел на сайт и создал хотя бы один блог |
| **Сценарий**           | Пользователь кликает на пункт «Search», находящийся в шапке сайта -> В появившемся списке пользователь выбирает пункт «Blogs» -> На открывшейся странице сайта пользователь вводит поисковый запрос в соответствующую форму ввода -> Пользователь нажимает кнопку «Search» -> После отображения результатов поиска, пользователь находит интересующий его блог |
| **Результат**          | Пользователь нашел нужный блог |


|      USE CASE 2        | ПОЛЬЗОВАТЕЛЬ НАХОДИТ СТАТЬЮ ПО НАЗВАНИЮ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Найти статью по названию |
| **Предусловие**        | Пользователь зашел на сайт и создал хотя бы один блог со статьями |
| **Сценарий**           | Пользователь кликает на пункт «Search», находящийся в шапке сайта -> В появившемся списке пользователь выбирает пункт «Posts» -> На открывшейся странице сайта пользователь вводит поисковый запрос в соответствующую форму ввода -> Пользователь нажимает кнопку «Search» -> После отображения результатов поиска, пользователь находит интересующую его статью |
| **Результат**          | Пользователь нашел нужную статью |


|      USE CASE 3        | ПОЛЬЗОВАТЕЛЬ ОТКРЫВАЕТ СТРАНИЦУ СТАТЬИ ДЛЯ ПРОСМОТРА |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Открыть страницу статьи для просмотра |
| **Предусловие**        | Пользователь зашел на сайт и нашел статью в поиске по названию |
| **Сценарий**           | Пользователь кликает на заголовок найденной ранее статьи |
| **Результат**          | Пользователь просмотрел информацию статьи |


|      USE CASE 4        | ПОЛЬЗОВАТЕЛЬ ОТКРЫВАЕТ СТРАНИЦУ БЛОГОВ ДЛЯ ПРОСМОТРА |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Открыть страницу блогов для просмотра |
| **Предусловие**        | Пользователь зашел на сайт и нашел блог по названию |
| **Сценарий**           | Система отображает список блогов вместе с их описанием -> Пользователь кликает на заголовок найденного ранее блога -> Система отображает список статей блога |
| **Результат**          | Пользователь просмотрел информацию блога |


|      USE CASE 5        | ПОЛЬЗОВАТЕЛЬ СОЗДАЕТ СТАТЬЮ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Создать статью |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу просмотра блогов |
| **Сценарий**           | Пользователь кликает на кнопку «Add new post» у соответствующего блога -> На появившейся форме пользователь заполняет данные нового поста -> Пользователь нажимает кнопку «Save» -> Система сохраняет всю введенную информацию в базе данных |
| **Результат**          | Создана статья с необходимой информацией |


|      USE CASE 6        | ПОЛЬЗОВАТЕЛЬ РЕДАКТИРУЕТ СТАТЬЮ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Редактировать статью |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу статьи для просмотра |
| **Сценарий**           | Пользователь кликает на кнопку «Edit» у соответствующей статьи -> На появившейся форме пользователь редактирует данные существующего поста -> Пользователь нажимает кнопку «Save» -> Система сохраняет всю введенную информацию в базе данных |
| **Результат**          | Информация статьи изменена на обновленную |


|      USE CASE 7        | ПОЛЬЗОВАТЕЛЬ УДАЛЯЕТ СТАТЬЮ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Удалить статью |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу статьи для просмотра |
| **Сценарий**           | Пользователь кликает на кнопку «Delete» у соответствующей статьи -> Система удаляет информацию о статье из базы данных |
| **Результат**          | Статья удалена из блогхоста |


|      USE CASE 8        | ПОЛЬЗОВАТЕЛЬ СОЗДАЕТ БЛОГ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Создать блог |
| **Предусловие**        | Пользователь зашел на сайт |
| **Сценарий**           | Пользователь кликает на пункт «My blogs», находящийся в шапке сайта -> В появившемся списке пользователь выбирает пункт «Add new» -> На появившейся форме пользователь заполняет данные нового блога -> Пользователь нажимает кнопку «Save» -> Система сохраняет всю введенную информацию в базе данных |
| **Результат**          | Создан блог с необходимой информацией |


|      USE CASE 9        | ПОЛЬЗОВАТЕЛЬ РЕДАКТИРУЕТ БЛОГ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Редактировать блог |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу блогов для просмотра |
| **Сценарий**           | Пользователь кликает на кнопку «Edit» у соответствующего блога -> На появившейся форме пользователь редактирует данные существующего блога -> Пользователь нажимает кнопку «Save» -> Система сохраняет всю введенную информацию в базе данных |
| **Результат**          | Информация блога изменена на обновленную |


|      USE CASE 10       | ПОЛЬЗОВАТЕЛЬ УДАЛЯЕТ БЛОГ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Удалить блог |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу блогов для просмотра |
| **Сценарий**           | Пользователь кликает на кнопку «Delete» у соответствующего блога -> Система удаляет информацию о блоге из базы данных |
| **Результат**          | Блог удален из блогхоста |


|      USE CASE 11       | ПОЛЬЗОВАТЕЛЬ СТАВИТ ЛАЙК |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Поставить лайк |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу статьи для просмотра |
| **Сценарий**           | Пользователь кликает на значок в форме сердца |
| **Результат**          | Система отображает поставленный лайк путем изменения цвета значка с серого на красный и сохраняет информацию в базе данных |


|      USE CASE 12       | ПОЛЬЗОВАТЕЛЬ ПИШЕТ КОММЕНТАРИЙ |
| :--------------------: | - |
| **Действующее лицо**   | Пользователь, система |
| **Цель**               | Написать комментарий |
| **Предусловие**        | Пользователь зашел на сайт и открыл страницу статьи для просмотра |
| **Сценарий**           | Пользователь вводит текст комментария в форму ввода находящуюся под основной информацией статьи -> Пользователь нажимает на кнопку «Comment» |
| **Результат**          | Система отображает новый комментарий и сохраняет информацию о нем в базу данных |

