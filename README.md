![Centurion logo](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_logo.png) 

# Centurion


Программное средство Centurion предназначено для проведения аудита информационной безопасности объектов вычислительной техники на базе операционных систем семейства Windows.

Для работы программы необходимо наличие [.NET Framework 4.5.2](https://www.microsoft.com/RU-RU/download/details.aspx?id=42642) или выше.

<a href="https://github.com/unchase/Centurion/releases/latest" target="_blank" rel="nofollow" style="vertical-align: -webkit-baseline-middle;"><img src="https://img.shields.io/github/downloads/unchase/centurion/total.svg?maxAge=86400&&style=flat-square" alt="GitHub Releases (latest)"></a> 
[![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/unchase/centurion.svg?style=flat-square)](https://github.com/unchase/Centurion/releases/latest)


## Supported OS
* Windows Vista
* Windows 7/8/8.1/10
* Windows Server 2008/2012/2016.

## Current status

Работа ведется над исправлением ошибок и тестированием beta-версии Centurion.

#### Version 1.0x BETA

<table>
  <tr>
    <th>&nbsp;</th>
    <th>Windows</th>
    <th>Linux/Mac</th>
  </tr>
  <tr>
    <td>Runtime environment</td>
    <td>MS Windows Vista <br/>MS Windows 7/8/8.1/10<br/>MS Windows Server 2008/2012/2016<br/>.NET Framework 4.5.2+</td>
    <td>No official support</td>
  </tr>
  <tr>
    <td>Development</td>
    <td><a href="https://visualstudio.microsoft.com" width="49%">MS VS 2017 v15.5+</a>, C#7.2, WPF</td>
    <td>No official support</td>
  </tr>
  <tr>
    <td><strong>Latest Pre-Release (v1.0 BETA)</strong></td>
    <td>GitHub: <a href="https://github.com/unchase/Centurion/releases" target="_blank"><img src="https://img.shields.io/github/downloads-pre/unchase/Centurion/latest/total.svg?maxAge=86400&&style=flat-square" alt="GitHub Releases (latest)"></a></td>
    <td>No official support</td>
  </tr>
</table>

### Commits statistics (on 13 august 2018)

Исходный код на Bitbucket (private repository) содержит <a href="https://bitbucket.org/unchase/Centurion/commits" target="_blank" rel="nofollow" style="vertical-align: -webkit-baseline-middle;"><img src="https://img.shields.io/badge/commits%20on%2013%20august,%202018-211-blue.svg?style=flat-square" alt="Bitbucket Commits (all)"></a>.<br/>

![Centurion commits](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_commits.png)
![Centurion commits2](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_commits2.png)

## How to get (get in beta-testing)

Чтобы получить файл лицензии для входа в [Centurion](http://github.com/unchase/centurion) необходимо отправить email-сообщение по адресу [centurionunchase@gmail.com](mailto:centurionunchase@gmail.com) с указанием желаемого срока окончания действия лицензии (например, "До 14 августа 2019 года") и именем для входа (например, "user"), в заголовоке письма указать - "Centurion License".<br/>
К email-сообщению необходимо прикрепить файл "license.bin", который будет создан в корневом каталоге программы при ее запуске.<br/><br/>
*Для каждого компьютера необходим отдельный файл лицензии "license.xml". При использовании программы на другом компьютере необходимо отправить заявку на получение файла лицензии повторно, прикрепив вновь сформированный на новом компьютере файл "license.bin".*

----------
Также можно воспользоваться кнопкой "Получить лицензию".<br/>

![Centurion login](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_login.gif)

## Features

### Registry
*Поддерживаются следующие функции, связанные с реестром Windows:*

- Поиск заданной строки ([регулярного выражения](https://wikipedia.org/wiki/Regular_expression)) в именах/значениях параметров и именах разделов реестра.
- Фильтрация: по диапазону дат, по типам данных, по способу сравнения. 
- Исключение определенных разделов реестра из поиска.
- Определение расхождений текущего состояния реестра с экспортированным файлом реестра с помощью [Regdiff](http://www.p-nand-q.com/download/regdiff.html).
- Уточнение (отбор) найденных значений.
- Удаление выбранных значений/разделов из реестра.
- Экспорт и печать результатов поиска.
- Эспорт/импорт реестра в файл. 
- Создание шаблонов поиска.

----------

![Centurion registry](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_registry.gif)

### File search
*Поддерживаются следующие функции, связанные с поиском в файловой системе:*

* [Полнотекстовый](https://wikipedia.org/wiki/Full-text_search) индексированный и не индексированный поиск строковых значений (регулярных выражений) в файлах.
* Фильтрация: по диапазону дат, размеру и расширениям файлов.
* Индексированный поиск на удаленных машинах.
* Управление индексацией Windows.
* Экспорт и печать результатов поиска.

----------

![Centurion filesystem search](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_filesystem_search.gif)

### Hardware and system information
* Получение информации о компьютере (на локальной и удаленной машине) с помощью [WMI](https://wikipedia.org/wiki/Windows_Management_Instrumentation).
* Поиск и экспорт данных в выведенных результатах.

----------

![Centurion hardware info](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_hardware_info.gif)

### System
* Получение различных данных о накопителях и логических дисках (тип, модель, вместимость, серийный номер и пр.).
* Получение физической геометрии, эксплуатационных качеств и состояния [S.M.A.R.T.](https://wikipedia.org/wiki/SMART) накопителей.
* Вывод записей из [MFT](https://wikipedia.org/wiki/Master_File_Table) логических дисков.
* Управление журналами событий Windows (создание, удаление, очистка, поиск событий).
* Управление службами Windows.
* Стирание информации о подключенных ранее к компьютеру USB-устройствах с помощью [USB Oblivion](https://www.cherubicsoft.com/projects/usboblivion).
* Управление утилитами [Nirsoft](http://www.nirsoft.net).
* **"Проводник безопасности"**.

----------

![Centurion system](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_system.gif)

### Security Browser

***"Проводник безопасности"** - файловый проводник Windows с множеством дополнительных функций:*

* Просмотр свойств компьютера, логических дисков, каталогов и файлов.
* Очистка свободного места на логических дисках (стирание следов, оставшихся после удаления файлов и каталогов).
* Гарантированное (безвозвратное) стирание файлов и каталогов с файлами.
* Изменение временных меток файла/каталога (время последней записи, доступа, модификации, создания), их обнуление (до минимального значения).
* Шифрование файлов (содержимого и имени) и каталогов с помощью выбранного алгоритма шифрования ([ГОСТ 28147-89](https://wikipedia.org/wiki/ГОСТ_28147-89), [AES](https://wikipedia.org/wiki/Advanced_Encryption_Standard), [Blowfish](https://wikipedia.org/wiki/Blowfish), [DES](https://wikipedia.org/wiki/DES) и др.).
* Проверка файлов на содержание вирусных сигнатур с помощью API [virustotal.com](http://virustotal.com).
* Управление [альтернативными потоками](https://ru.wikipedia.org/wiki/Альтернативные_потоки_данных) данных в файловой системе NTFS.
* Разграничение доступа к файлам/каталогам [ACL](https://wikipedia.org/wiki/Access_control_list).
* Определение типа файла по его сигнатуре (с использованием [TrID](http://mark0.net/soft-trid-e.html)).
* Вычисление контрольных-сумм файлов ([CRC32](https://wikipedia.org/wiki/Cyclic_redundancy_check), [CRC64](https://wikipedia.org/wiki/Cyclic_redundancy_check), [MD5](https://wikipedia.org/wiki/MD5), [ГОСТ 34.11-2012](https://wikipedia.org/wiki/Streebog), [SHA256](https://wikipedia.org/wiki/SHA-2), [SHA512](https://wikipedia.org/wiki/SHA-2)).
* Получение метаданных мультимедиа-файлов с помощью [Metadata Extractor](https://github.com/drewnoakes/metadata-extractor).

----------

<img src="https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_security_browser.gif" width="49%"></img> <img src="https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_security_browser2.gif" width="49%"></img>

### Data shreder
* Очистка свободного места на логическом диске (стирание следов, оставшихся после удаления файлов и каталогов).
* Гарантированное (безвозвратное) стирание файлов и каталогов с файлами с возможностью выбора метода стирания ([ГОСТ 50739-95](http://docs.cntd.ru/document/gost-r-50739-95), DOD 5220.22-M, Peter Gutmann, Bruce Shneier и др.).

----------

![Centurion shrefer](https://raw.githubusercontent.com/unchase/centurion/master/images/centurion_shreder.gif)

## Shoutouts
* [Nirsoft](http://www.nirsoft.net) by [Nir Sofer](mailto:nirsofer@yahoo.com)
* [USB Oblivion](https://www.cherubicsoft.com/projects/usboblivion) by [Николай Распопов](https://plus.google.com/113807765564201615331?rel=author)
* [Regdiff](http://www.p-nand-q.com/download/regdiff.html) by [Gerson Kurz](http://www.p-nand-q.com) ([Liberal BSD-style license](http://www.linfo.org/bsdlicense))
* [Metadata Extractor](https://github.com/drewnoakes/metadata-extractor) by [Drew Noakes](https://github.com/drewnoakes) ([Apache License 2.0](https://github.com/drewnoakes/metadata-extractor/blob/master/LICENSE))

## Links
* Source code (private repository): <a href="https://bitbucket.org/unchase/centurion" target="_blank" rel="nofollow" style="vertical-align: -webkit-baseline-middle;"><img src="https://img.shields.io/badge/Bitbucket%20source%20code%20(private%20repository)-go-blue.svg?style=flat-square" alt="Bitbucket Source code (private repository)"></a>
* Issue tracker: [![GitHub issues](https://img.shields.io/github/issues/unchase/centurion/shields.svg?style=flat-square)](https://github.com/unchase/Centurion/issues) [![GitHub issues-closed](https://img.shields.io/github/issues-closed/unchase/centurion.svg?style=flat-square)](https://GitHub.com/unchase/centurion/issues?q=is%3Aissue+is%3Aclosed)
* Website: [![Website centurion.unchase.ru](https://img.shields.io/website-up-down-green-red/http/centurion.unchase.ru.svg?style=flat-square)](http://centurion.unchase.ru/)
* Wiki: <a href="https://github.com/unchase/centurion/wiki" rel="nofollow" target="_blank" style="vertical-align: -webkit-baseline-middle;"><img src="https://img.shields.io/badge/Wiki-go-blue.svg?style=flat-square" alt="Github Wiki"></a>
