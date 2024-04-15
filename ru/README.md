
# Инструкция по настройке LunaTranslator

<p align="left">
    <a href="./LICENSE"><img src="https://img.shields.io/badge/license-GPL%203.0-dfd.svg"></a>
    <a href="https://github.com/HIllya51/LunaTranslator/releases"><img src="https://img.shields.io/github/v/release/HIllya51/LunaTranslator?color=ffa"></a>
    <a href="https://github.com/HIllya51/LunaTranslator/stargazers"><img src="https://img.shields.io/github/stars/HIllya51/LunaTranslator?color=ccf"></a>
     
</p> 
 
<a id="table1"></a>

## Основные функции:

#### Выбор источника текста

&emsp;&emsp;**Буфер обмена** Копирование текста из буфера обмена для перевода.

&emsp;&emsp;**OCR** Поддерживает автономные считывальщики текста с экрана Paddle OCR и WindowsOCR, а также онлайн сервисы: Baidu OCR, Youdao OCR, OCRspace, docsumo. Также поддерживает привязку и скрытие окон для распознавания текста с экрана для удобной игры.

&emsp;&emsp;**HOOK** Поддерживает использование HOOK для получения текста из данных игры, поддерживает использование специальных кодов, поддерживает автоматическое сохранение игр, а также автоматическую загрузку HOOK во время запуска игр.


#### Выбор переводчика

Поддерживает почти все существующие механизмы перевода, в том числе:

&emsp;&emsp;**Автономный перевод** Поддержка автономного перевода с использованием JBeijing 7, Jinshan Quick Translation и Yidiantong (Не работает для перевода на русский язык).

&emsp;&emsp;**Бесплатный онлайн-перевод** Поддержка Baidu, Bing, Google, Ali, Youdao, Caiyun, Sogou, DeepL, Kingsoft, Xunfei, Tencent, Byte, Volcano, papago, yeekit и других онлайн-сервисов.

&emsp;&emsp;**Онлайн-перевод с регистрацией ключа API** Поддержка перевода с использованием зарегистрированных пользователем ключей перевода для Baidu, Tencent, Youdao, Mavericks, Caiyun, Volcano, Deepl и других.

&emsp;&emsp;**Предварительный перевод** Поддержка чтения файлов предварительного перевода, выполненных человеком, и агрегация машинных файлов.

&emsp;&emsp;**Поддержка пользовательских расширений перевода** Поддержка использования языка python для расширения других интерфейсов перевода, о которых я не знаю.

#### Синтез речи/Озвучка текста

&emsp;&emsp;**Offline TTS** Поддержка windowsTTS, VoiceRoid2 и VOICEVOX.

&emsp;&emsp;**Online TTS** Поддержка AzureTTS и Volcano TTS.

#### Обработка текста/Оптимизация перевода

&emsp;&emsp;**Обработка текста** Поддерживает простую обработку, такую, как дедупликация текста, фильтрация HTML-тегов, фильтрация разрывов строк, фильтрация символов и чисел, поддержка пользовательской простой замены текста и замены с использованием регулярных выражений.

&emsp;&emsp;**Оптимизация перевода** Поддерживает использование собственных корректировок перевода и импорт общих словарей VNR.

#### Японская письменность

&emsp;&emsp;**Сегментация японских слов и отображение каны** Поддержка использования встроенных бесплатных загружаемых инструментов сегментации слов и отображения каны, поддержка использования Mecab для оптимизации сегментации слов и отображения каны, поддержка сторонних словарей.

&emsp;&emsp;**Поиск слов** Поддержка поиска слов с использованием Xiaoxiaoguan, Lingoes Dictionary и EDICT (японо-английский словарь).

## Скачать дополнительные файлы:

<table>

<tr><td>OCR- упрощенный китайский язык</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.34.5/zh.zip">zh.zip</a></td></tr>
<tr><td>OCR- китайский язык</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.34.5/cht.zip">cht.zip</a></td></tr>
<tr><td>OCR- корейский</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.34.5/ko.zip">ko.zip</a></td></tr>
<tr><td>Словарь MeCab</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/Mecab.zip">Mecab.zip</a></td></tr>
<tr><td>Словарь Xiaoxiaoguan</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/xiaoxueguan.db">xiaoxueguan.db</a></td></tr>
<tr><td>Словарь EDICT</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/edict.db">edict.db</a></td></tr>

<tr><td>Словарь EDICT2</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.1.2/edict2">edict2</a></td></tr>
<tr><td>Словарь JMdict</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.1.2/JMdict.xml">JMdict.xml</a></td></tr>
<tr><td>Словарь Lingoes</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/Lingoes.zip">Lingoes.zip</a></td></tr>
<tr><td>Переводчик JBeijing7</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/JBeijing7.zip">JBeijing7.zip</a></td></tr>
<tr><td>Переводчик FastAIT</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/FastAIT09_Setup.25269.4101.zip">FastAIT09_Setup.25269.4101.zip</a></td></tr>
<tr><td>Переводчик DR.eye</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/DR.eye.zip">DR.eye.zip</a></td></tr>
<tr><td>Эмулятор для запуска новелл </td><td><a href="https://github.com/xupefei/Locale-Emulator/releases/download/v2.5.0.1/Locale.Emulator.2.5.0.1.zip">Locale.Emulator.2.5.0.1.zip</a></td></tr>
<tr><td>Голос VoiceRoid2</td><td><a href="https://github.com/HIllya51/LunaTranslator/releases/download/v1.0/Yukari2.zip">Yukari2.zip</a></td></tr>
<tr><td>Голос VOICEVOX</td><td><a href="https://github.com/VOICEVOX/voicevox/releases/download/0.13.3/voicevox-windows-cpu-0.13.3.zip">voicevox-windows-cpu-0.13.3.zip</a></td></tr>
</table>