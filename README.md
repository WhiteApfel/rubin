# РуБИН

Я опять выпил две чашки кофе на ночь, поэтому меня посетило множество бредовых идей.
Одной из них оказалось агрегирование БИНов в одно место, учитывая социально-незащищенные филиалы крупных банков и
всякие финтех-стартапы. Добавлю всё, куда хватит глаз. Может ещё и другие данные банков соберу до кучи. Посмотрим.

## Откуда ты всё взял?

Посмотрел публичные бин-базы, потыкал react- и nuxt-приложения, прошёлся по апишкам. Вот они слева направо.

### Открытые базы и проверяльщики:
* BinCheck.org
    * [Российские БИН'ы](https://bincheck.org/russia)
* FreeBinChecker.com
    * [Российские БИН'ы](https://www.freebinchecker.com/russian-federation-bin-list)
    * [Проверка с капчей](https://www.freebinchecker.com/)
    * [Более точная проверка без капчи](https://www.freebinchecker.com/bin-checker/)
* GetBinCodes.com
    * [Российские БИН'ы](https://www.getbincodes.com/country-russia/)
* BinTable
    * [Российские БИН'ы](https://bintable.com/country/ru)
* Psm7.com
    * [Достаточно точная проверка с капчей](https://psm7.com/bin-card)
* BinCheck.io
    * [Проверка без капчи](https://bincheck.io/)
    * [Российские БИН'ы по банкам](https://bincheck.io/ru)
    * [Удобный поиск БИН'ов по фильтрам](https://bincheck.io/bin-search)
* iBankie.com
    * [Российские БИН'ы](https://ibankie.com/ru/banks/ru/russian-standard-bank/bins)

### Банки и сервисы с бинами в JS:
* Yoomoney
    * [Страница c2c](https://yoomoney.ru/transfer/a2c)
* Ак Барс
    * [Страница c2c](https://ecom.akbars.ru/cgi-bin/cgi_link?TERMINAL=93200011)
* Русский Стандарт
    * [Страница c2c](https://www.rsb.ru/platezhi-perevody/s-karty-na-kartu/)

### Банки и сервисы с проверкой бинов по API:
* Тинькофф
    * [Страница c2c](https://www.tinkoff.ru/cardtocard/)
* Альфабанк Беларусь
    * Веб у них реально годнота годная, не то что в Эрафии
    * [Страница c2c](https://perevod.alfabank.by/payment/merchants/p2p_transferhub_v2/index.html)
* Точка
    * Нужно авторизоваться
    * [Страница c2c](https://x.tochka.com/m/card_payment)
* PaySand
    * Нужно авторизоваться
    * [Страница c2c](https://paysend.com/auth/send)
