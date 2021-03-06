# dropbox #

* Authors: Patrick ZAJDA <patrick@zajda.fr>, Filaos and other contributors
* Download [stable version][1]
* Download [development version][2]

هدف این افزونه ایجاد کلید میانبر برای اعلام وضعیت و نسخه فعلی Dropbox و باز
کردن منوی Dropbox در system tray میباشد. همچنین داخل تنظیمات Dropbox با
کلیدهای Ctrl+tab / Ctrl+Shift+Tab و Ctrl+PageUp/Down میتوان بین صفحات مختلف
حرکت کرد. بعد از اتمام کار داخل تنظیمات Dropbox میتوانید با کلید گریز دکمه
انصراف را فعال کرده از صفحه خارج شوید.

* Shortcut: NVDA+Alt+D
* Ctrl+Alt+T صفحه فعال را اعلام میکند

## مسائل شناخته شده ##

* اگر با استفاده از کلیدهای میانبر بین صفحات حرکت بکنید, موقعی که پنجره تنظیمات را میبندید, NVDA قادر نخواهد بود پنجره هایی را که دیگر وجود ندارند را بشناسد.
این یک مسئله شناخته شده است و قابل حل نیست.


## Changes for 4.4 ##

* Python 3 compatibility
* Use the last addon template
* Repository change to be built with Appveyor

## Changes for 4.0 ##

* Add-on help is available from the Add-ons Manager.
* The shortcut to get Dropbox status has been changed to Alt+NVDA+D to avoid
  conflict with audio ducking support.

## تغییرات داده شده در نسخه 3.1 ##

* از روش دیگری برای پیدا کردن دکمه انصراف و حرکت بین صفحات استفاده
  بکنید. فعلا" قبلا" از اینکه از کلید میانبرها استفاده بکنید مجبور نیستید
  روی صفحه متمرکز بشوید.
* موقع تغییر صفحه فعال, فوکوس به صفحه فعال میرود بنابراین موقع فشار دادن
  دکمه tab, اولین آیتم صفحه فعال میشود بجای اینکه در صفحه قبلی استفاده شده
  بماند حتا اگر فعال نشده باشد.
* داخل صفحه تنظیمات, در حال حاضر میتوانید بین صفحات با کلیدهای control+page
  up/down حرکت بکنید. Control+tab و control+shift+tab نیز کار میکند.
* همه پرونده های بومی شده manifest حالا باید بدرستی کار بکند.
* اصلاحات جزیى.

## تغییرات داده شده در نسخه 3.0 ##

* اصلاح جزیى در پرونده اصلی manifest (سازندگان بدرستی نشان داده میشوند).
* باز کردن منوی Dropbox موقع فشار دادن سه بار Shift+NVDA+D اصلاح شد
* دکمه گریز حالا (فقط موقعی که Dropbox از همان زبانی که NVDA استفاده میکند)
  کار میکند.
* اصلاحات بسایر در کد.
* اسناد تمامی اسکریپتها به روز رسانی/اضافه شده اند.
* زبانهای جدید: عربی، پرتغالی برزیل، چک، هلندی، فنلاندی، گالیسی، آلمانی،
  مجارستانی، ژاپنی، نپالی، لهستانی، روسی، اسپانیایی، اسلواکی، تامیلی، ترکی
  استانبولی.

## تغییرات داده شده در نسخه 2.0 ##

* زبانهای جدید: ایتالیایی
* فشار دادن سه بار یا بیشتر کلید میانبر داخل منو مشکلی بوجود نمیآورد.

## تغییرات داده شده در نسخه 1.0 ##

* انتشار اولیه

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=dx

[2]: https://addons.nvda-project.org/files/get.php?file=dx-dev
