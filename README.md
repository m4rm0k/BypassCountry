# BypassCountry

Класс для блокировки определённых стран методом завершения работы программы.
Как работает данный класc?

Ответ: 
Сначала класс определяет страну из онлайн сервиса: [http://ip-api.com/line/?fields=country](http://ip-api.com/line/?fields=country)
Затем проверяет найденную страну с нашим списком стран и если находит совпадения то программа завершает свою работу.

P.S: Если не желаете использовать онлайн сервисы, то для этого есть альтернатива использования класса [CultureInfo](https://docs.microsoft.com/ru-ru/dotnet/api/system.globalization.cultureinfo?view=netframework-4.8)
