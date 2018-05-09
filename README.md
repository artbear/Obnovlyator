# Обновлятор

Комплект скриптов на OneScript, помогающих в обновлении конфигурации поставщика информационных баз 1С:Предприятие, а также в переносе обновленной конфигурации между различными информационными базами.

Реализовано на OneScript (http://oscript.io). Для работы необходим OneScript версии 1.0.20 или выше.

## Описание

Подробное описание и приницип работы в этом видео: https://youtu.be/GCjgDgGg-gc

## Установка

### Зависимости  

Необходима библиотека **json**: https://github.com/oscript-library/json

Установка:
``` cmd
opm install json
```

Необходим набор библиотек **TLib** : https://github.com/Tavalik/OS_TScripts/tree/master/Tlib

Установка копированием каталога Tlib в каталог библиотек (по умолчанию в C:\Program Files (x86)\OneScript\lib)

### Установка приложения

Установка копированием файлов текущего репозитория.

## Описание и работа с приложением

Набор состоит из двух скрипотов:

* Скрипт1_ОбновлениеРазработочной.os
* Скрипт2_ПереносОбновленияВСборку.os

При первом запуске скрипта **Скрипт1_ОбновлениеРазработочной.os**  в текущем каталоге будет создан пустой файл настроек **Obnovlyator_Params.json** и каталог **Files**.

После заполнения всех параметров, какждый из этапов обновления осуществляется запуском соответствющего скрипта.