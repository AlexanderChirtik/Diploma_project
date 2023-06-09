GEEKBRAINS

Факультет Разработчик — Программист. Специализация

ДИПЛОМНЫЙ ПРОЕКТ

**«Программа по автоматическому внесению информации о получателях услуг в установленные формы»**

Выполнил:

*Чиртик Александр 
Александрович*

г. Кемерово
2023 г.

<br>
<br>
Содержание

## Введение………………………………………………………………………….

## Глава 1. Ввод необходимых данных и их обработка………………………..

### 1.1.	Создание интерфейса для ввода данных…………………………………….

### 1.2.	Соединение созданных интерфейсов с разработанной программой на языке Java……………………………………………………………….

### 1.3.	Перенос данных из интерфейса ввода в установленные формы документов с расширением Word…………………………………………….

## Глава 2. Передача данных между устройствами……………………………….

### 2.1. Передача готовых документов из множества компьютеров на основной компьютер…………………………………………………………………………….

## Глава 3. Хранение готовых и выпущенных документов

### 3.1. Создание базы данных на основном компьютере……………………………….

## Заключение………………………………………………………………………….

## Список используемой литературы………………………………………………..

## Приложения…………………………………………………………………………..      
<br>

## Введение

**Актуальность выбранной темы.** В рамках недавней деятельности мне приходилось в большом количестве работать с личными документами граждан. А так как работа по моему направлению деятельности была во многом уникальна, не было возможности передать данные функции другому специалисту. Да и в целом выполнять достаточно монотонную работу в современном мире – это уже некая архаичность. Поэтому перед моей организацией встал вопрос об усовершенствовании данной работы и её перевода в цифровой формат. 
Именно поэтому в качестве дипломного проекта я решил выбрать решение данной проблемы. На мой взгляд, создание отдельного десктопного приложения специально для этой задачи является конструктивным решением. Моя идея заключается в том, чтобы создать программу для операционной системы Windows, которая будет установлена на множестве компьютеров (пункты приема документов). У данной программы будет один пользователь с административными функциями, а все остальные смогут только вносить данные в установленные формы и отправлять их на административный компьютер. При внесении данных на метах они будут автоматически вноситься в установленные формы документов. Дальше сотрудник пункта приема документов прикрепляет в этой программе сканы оригиналов документов гражданина и отправляет их. В программе на компьютере администратора должна быть функция хранения и распечатывания указанных документов.

**Целью** данной работы является создание полноценного десктопного приложения, которое сможет объединить несколько компьютеров в единую сеть, и передавать на основной компьютер выбранные формы документов, заполненные на местах. Основной же компьютер сможет хранить у себя документы в созданной базе данных.

**Цель данной работы потребовала сформулировать следующие задачи:**

**Во-первых**, разработать интерфейс для ввода данных из оригиналов документов.

**Во-вторых**, создать способ внесения данных из полей, указанных выше, в выделенные строки в документах формата doc. Подключить сторонние библиотеки для работы с Word.

**В-третьих**, применить безопасный способ передачи данных между устройствами, участвующими в работе с личными данными пользователей.

**В-четвёртых**, создание на основном компьютере базы данных, в которой будут храниться все присылаемые документы.

**Структура работы**. Данная работа состоит из введения, трех глав, заключения, списка использованной литературы и источников и приложения. 

**Инструменты**: IntelliJ IDEA.
