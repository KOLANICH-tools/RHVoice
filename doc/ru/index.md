[English](doc/en/index.md) / Русский

# Документация RHVoice

<details>
<summary>
О синтезаторе речи
</summary>

## Возможности

### Метод синтеза речи

RHVoice использует статистический параметрический синтез. Он опирается на уже
существующие речевые технологии с открытым исходным кодом (прежде всего
[HTS](http://hts.sp.nitech.ac.jp) и связанные компоненты).

Голоса создаются на основе записей естественной человеческой речи. Они
компактны, так как на компьютере пользователей хранятся только статистические
модели. И хотя голосам не хватает естественности тех синтезаторов, которые
генерируют речь, комбинируя фрагменты самих записей, они всё же очень разборчивы
и напоминают дикторов, которые записали исходный материал.

### Поддерживаемые языки

Изначально RHVoice говорил только по-русски. Теперь он также поддерживает
американский английский, бразильский португальский, эсперанто, грузинский,
украинский, киргизский и татарский. Теоретически, поддержка других языков может
быть реализована, если удастся найти или создать все необходимые ресурсы.

### Пример синтеза

Если вы хотите прослушать пример синтеза речи, вы можете перейти на
[эту страницу.](https://data2data.ru/tts/)

### Поддерживаемые платформы

RHVoice поддерживает Windows, GNU/Linux и Android. Он совместим со стандартными
интерфейсами преобразования текста в речь на этих платформах SAPI5 в Windows,
[Speech Dispatcher](http://devel.freebsoft.org/speechd) в GNU/Linux и API для
преобразования текста в речь в Android. Он также может использоваться
[скринридером NVDA](http://www.nvaccess.org) напрямую (драйвер предоставляется
самим RHVoice).
</details>

## Основная информация

* [Готовые сборки](doc/ru/Binaries.md)
* [Файл конфигурации](doc/ru/Configuration-file.md)

## Инструкции по сборке

* [Компиляция на Linux](doc/ru/Compiling-on-Linux.md)
* [Состояние пакетов](doc/ru/Packaging-status.md)

## Правовая информация

* [Лицензия](doc/ru/License.md)
* [Политика конфиденциальности](doc/ru/Privacy.md)
