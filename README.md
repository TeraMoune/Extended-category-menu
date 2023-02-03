# Extended category menu
Плагин расширяющий возможности формирования меню категорий при использовании тега `{catmanu}`

Версия DLE: 14.3 (На более ранних не проверялось)

## Возможности:
* Можно менять порядок сортировки по нескольким полям в отдельных разделах (**addnews**, **search** и раздел категорий администраторской панели) в `$order_category_ex` массиве. (**name**, **newscount**, **rating_sum**, **id**, **comm_sum**, **newsread_sum**, **votenum_sum**)
* Для изменения порядка сортировки у тега `{catmenu}` можно использовать параметр **sort** с одним из этих значений.
* Тегу `{catmenu}` добавлен параметр **limit** ограничивающий количество категорий.
* В шаблонах меню можно использовать новые теги: **{rating_sum}**, **{comment_sum}**, **{newsread_sum}**, **{vote_sum}**. Которые выводят общее значение показателей.
* Два блочных тега **[not-category=X] ... [not-category]** и **[category=X] ... [/category]** используемые в рамках тега **[item]**.

:exclamation: Информация по первому пункту находится в заметках плагина.
