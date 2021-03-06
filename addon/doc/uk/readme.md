# dropbox #

* Authors: Patrick ZAJDA <patrick@zajda.fr>, Filaos and other contributors
* Завантажити [стабільну версію][1]
* Download [development version][2]

Цей плагін додає клавіатурне скорочення, за допомогою якого можна дізнатися
про поточний стан Dropbox, його версію та відкрити меню Dropbox з системної
панелі. Також працює сторінка вкладок над діалогом параметрів з комбінаціями
ctrl+tab/ctrl+shift+tab та ctrl+сторінка Вгору/Вниз. Для завершення
натисніть клавішу скасування, якою є клавіша ескейп.

* Shortcut: NVDA+Alt+D
* Ctrl+Alt+T промовляє активну вкладку.

## Відомі проблеми ##

* Якщо ви перемикаєтеся між вкладками, використовуючи гарячі клавіші, то коли ви закриєте вікно з параметрами, NVDA не буде знати, що цього вікна більше неіснує.
Це відома проблема в NVDA, яку неможливо виправити.


## Changes for 4.4 ##

* Python 3 compatibility
* Use the last addon template
* Repository change to be built with Appveyor

## Зміни у версії 4.0 ##

* Add-on help is available from the Add-ons Manager.
* The shortcut to get Dropbox status has been changed to Alt+NVDA+D to avoid
  conflict with audio ducking support.

## Зміни у версії 3.1 ##

* Використовуйте інший спосіб щоб отримати кнопку "Скасувати" або вкладку
  сторінки. Тепер не треба їх фокусувати перед використанням гарячих клавіш.
* When changing the active tab, the focus move to the tab page so when
  pressing tab, the first item of the tab is activated instead of staying to
  the previous used tab even if it is not activated anymore.
* У діалозі параметрів можна перемикатися між вкладками за допомогою
  комбінацій control+сторінка Вгору/control+сторінка Вниз. Крім того,
  комбінації control+tab/control+shift+tab працюють як і раніше.
* Усі локалізовані manifest-файли мають бути в порядку.
* Невеличкі виправлення.

## Зміни у версії 3.0 ##

* Невеличке виправлення у головному manifest-файлі (імена авторів тепер
  відображаються коректно).
* Поліпшено виявлення контекстного меню при потрійному натисканні
  Shift+NVDA+D.
* Клавіша ескейп зараз працює (лише за умови, якщо Dropbox використовує ту ж
  саму мову, що й NVDA).
* Низка виправлень у коді.
* Додано/оновлено документацію для усіх скриптів.
* Нові мови: арабська, Галісійська, іспанська, непальська, нідерландська,
  німецька, польська, португальська (Бразилія), російська, словацька,
  тамільська, турецька, угорська, фінська, чеська і японська.

## Зміни у версії 2.0 ##

* Нова мова: італійська
* Натискання гарячих клавіш три або більше разів під час перебування у
  контекстному меню більше не викликає проблем.

## Зміни у версії 1.0 ##

* Перший реліз

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=dx

[2]: https://addons.nvda-project.org/files/get.php?file=dx-dev
