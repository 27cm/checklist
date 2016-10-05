
# Чеклист веб-разработки <img src="https://raw.githubusercontent.com/27cm/checklist/master/media/logo.png" alt="Web Development Checklist" align="right" width="60">

> Чеклист – очень важная, полезная и удобная вещь. Смысл чеклиста в том, что ты 
> проходишься по каждому пункту, отвечая себе на вопрос «Выполнен ли этот пункт?».


## Оглавление

- [PHP](#php)
- [HTML](#html)
- [CSS](#css)
- [JS](#js)
- [SEO](#seo)
- [Безопасность](#security)
- [UI](#ui) 
- [Дизайн](#design)
- [Linux](#linux)
- [Прочее](#etc)


## <a name='php'></a>PHP
*На основе рекомендаций [PHP: The Right Way](http://www.phptherightway.com), [RuHighload](http://ruhighload.com/index.php/2009/06/03/php-%D1%80%D0%B5%D1%86%D0%B5%D0%BF%D1%82%D1%8B-%D0%B8-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-%D0%BF%D0%BE%D0%B4-%D0%B1%D0%BE%D0%BB%D1%8C%D1%88%D0%B8%D0%B5-%D0%BD%D0%B0%D0%B3%D1%80/)*

- [ ] Используй последнюю стабильную версию PHP
      <br>*[php.net/releases/index.php](https://php.net/releases/index.php)*
- [ ] Используй любой современный PHP фреймворк
      <br>*[Laravel](http://laravel.com/),
      [Symfony](http://symfony.com/),
      [Zend Framework](http://framework.zend.com/),
      [Yii](http://www.yiiframework.com/)*
- [ ] Следуй рекомендациям PSR
      <br>*[php-fig.org](http://php-fig.org/)*
- [ ] Используй стандартную библиотеку PHP (SPL)
      <br>*[php.net/manual/ru/book.spl.php](http://php.net/manual/ru/book.spl.php)*
- [ ] Используй готовые библиотеки, не изобретай «велосипеды»
      <br>*[github.com/ziadoz/awesome-php](https://github.com/ziadoz/awesome-php)*
- [ ] Автоматизируй тестирование
      <br>*[PHPUnit](https://phpunit.de/), [Codeception](http://codeception.com/)*
- [ ] Используй FastCGI / PHP-FPM для ускорения работы скриптов
      <br>*[php-fpm.org](http://php-fpm.org)*
- [ ] Используй OpCache для увеличение производительности интерпретатора при обработке сценариев
      <br>*[php.net/manual/book.opcache.php](http://php.net/manual/book.opcache.php)*
- [ ] Используй APC / Memcache / Redis для кеширования данных


## <a name='html'></a>HTML

- [ ] Валидность
      <br>*[validator.w3.org](http://validator.w3.org)*
- [ ] Оптимизация для мобильных устройств
      <br>*[validator.w3.org/mobile](http://validator.w3.org/mobile/)*
- [ ] Интеграция в пользовательское окружение
      <br>*[buildmypinnedsite.com](http://www.buildmypinnedsite.com/en)*
      <br>*[api.yandex.ru/tableau](http://api.yandex.ru/tableau/)*
      <br>*[List of Usable HTML Meta and Link Tags](https://gist.github.com/kevinSuttle/1997924)*
- [ ] Правильная типографика
      <br>*[habrahabr.ru/post/57351](http://habrahabr.ru/post/57351/)*
- [ ] Отсутствие опечаток, орфографических и пунктуационных ошибок


## <a name='css'></a>CSS

- [ ] Работоспособность (читаемость) с выключенными стилями
      <br>*[achecker.ca/checker](http://achecker.ca/checker/)*
- [ ] Отсутствие проблем в вёрстке из-за расширений браузеров
      <br>*[Советник Яндекс.Маркета](https://sovetnik.yandex.ru/), [Skype Click to Call](http://achecker.ca/checker/), [Adblock Plus](https://adblockplus.org/), [uBlock](https://www.ublock.org/), [NoScript](https://noscript.net/)*
- [ ] Соответствие макету<br>
- [ ] Кроссбраузерность
      <br>*[developer.chrome.com/devtools/docs/device-mode](https://developer.chrome.com/devtools/docs/device-mode)*
      <br>*[browserstack.com](https://www.browserstack.com/)*
      <br>*[dev.windows.com/en-us/microsoft-edge/tools](https://dev.windows.com/en-us/microsoft-edge/tools/)*
- [ ] Валидность
      <br>*[jigsaw.w3.org/css-validator](http://jigsaw.w3.org/css-validator/)*
- [ ] Наличие Windows/Mac/Linux аналогов шрифтов
      <br>*[cssfontstack.com](http://cssfontstack.com/)*
- [ ] Версия для печати
      <br>*[developer.chrome.com/devtools/docs/device-mode](https://developer.chrome.com/devtools/docs/device-mode#more-media-types)*
- [ ] Mobile first, Progressive enhancement, Graceful degradation


## <a name='js'></a>JavaScript
*На основе рекомендаций [JavaScript: The Right Way](http://jstherightway.org)*

- [ ] Работоспособность с выключенными JavaScript и Flash
- [ ] Используй любой современный JavaScript фреймворк
      <br>*[todomvc.com](http://todomvc.com/)*
- [ ] Используй готовые библиотеки, не изобретай «велосипеды»
      <br>*[github.com/sorrycc/awesome-javascript](https://github.com/sorrycc/awesome-javascript)*
- [ ] Автоматизируй тестирование
      <br>*[Mocha](http://mochajs.org/),
      [QUnit](http://qunitjs.com/),
      [Jasmine](https://github.com/pivotal/jasmine),
      [Karma](http://karma-runner.github.io/),
      [Intern](http://theintern.io/)*


## <a name='seo'></a>SEO

- [ ] Канониназация домена, регистра, слешей и дефисов в URL
      <br>*`http://www.DOMAIN.com/section///PAGE---name/ > http://domain.com/section/page-name`*<br>
      [no-www.org](http://no-www.org)
- [ ] ЧПУ
      <br>*[ru.wikipedia.org/wiki/ЧПУ](https://ru.wikipedia.org/wiki/%D0%A7%D0%9F%D0%A3_(%D0%98%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82))*
- [ ] Оптимизация скорости загрузки страниц
      <br>*[developers.google.com/speed/pagespeed/insights](https://developers.google.com/speed/pagespeed/insights/)*
      <br>*[yslow.org](http://yslow.org/)*
- [ ] Оптимизация для мобильных устройств
      <br>*[google.com/webmasters/tools/mobile-friendly](https://www.google.com/webmasters/tools/mobile-friendly/)*
- [ ] Микроформаты
      <br>*[schema-creator.org](http://schema-creator.org/)*
      <br>*[schema.org](http://schema.org/)*
      <br>*[w3.org/2003/12/semantic-extractor](http://www.w3.org/2003/12/semantic-extractor.html)*
- [ ] Sitemaps
      <br>*[sitemaps.org/ru](http://www.sitemaps.org/ru/)*
- [ ] robots.txt
      <br>*[robotstxt.org](http://www.robotstxt.org/)*
- [ ] humans.txt
      <br>*[humanstxt.org](http://humanstxt.org/)*
- [ ] Оптимизация постраничной навигации
      <br>*[seoprofy.ua/blog/optimizaciya-sajtov/pagination-for-seo](http://seoprofy.ua/blog/optimizaciya-sajtov/pagination-for-seo)*
- [ ] Редирект 301 Moved Permanently
      <br>*Постоянный редирект, который передает около 90-99% ссылочного веса. Указывает, что
      страница перемещена по новому адресу и старый url следует считать устаревшим.*
      <br>*[seoprofy.ua/blog/optimizaciya-sajtov/301-redirekt](http://seoprofy.ua/blog/optimizaciya-sajtov/301-redirekt)*
- [ ] Редирект 302 Found
      <br>*Временный редирект, который передает 0% ссылочного веса.
      В большинстве случаев, не должен использоваться.*


## <a name='security'></a>Безопасность

- [ ] Не храни пароли в открытом виде.
      <br>*Даже в логах заменяй все пароли и токены на &star;&star;&star;*
- [ ] Хеширование паролей должно быть стойким к атакам перебора, с использованием «соли».
      <br>*Например [Bcrypt](https://ru.wikipedia.org/wiki/Bcrypt) с количеством раундов не менее 2<sup>10</sup>*
- [ ] Следуй 9.5 правилам ведения безопасного IT-бизнеса в России:
      [blog.micromarketing.ru/advice/9-point-5-rules-fot-it-business-in-russia](http://blog.micromarketing.ru/advice/9-point-5-rules-fot-it-business-in-russia/)
- [ ] Ограничение несанкционированного доступа к файлам, страницам и сообщениям об ошибках.
- [ ] Защита сайта от межсайтовой подделки запросов (CSRF).
      *Не только POST, но любых других запросов.*
- [ ] Защита от выполнения несанкционированных запросов к базе данных (SQL инъекций).
- [ ] Защита от межсайтового скриптинга (XSS):
      - [ ] Фильтрация входных данных, кодирование любых управляющих HTML-символов, JavaScript, CSS и URL перед отображением в браузере.
      - [ ] Регулярный ручной и автоматизированный анализ безопасности кода и тестирование на проникновение. С использованием таких инструментов, как Nessus, Nikto Web Scanner и OWASP Zed Attack Proxy.
      - [ ] Указание кодировки UTF-8 на каждой странице до каких-либо пользовательских полей.
      - [ ] Обеспечение безопасности HTTP cookie путём ограничения домена и пути для принимаемых значений, установки параметра HttpOnly или использованием SSL.
      - [ ] Использование заголовка Content Security Policy.
- [ ] Обеспечение безопасного соединения между сервером и браузером пользователя при передаче персональной информации и проведении финансовых операций на сайте по протоколу TLS (мультидоменная SSL сертификация).
- [ ] Протоколирование всех возникающих ошибок и предупреждений. Уведомление разработчиков о возникающих ошибках. Ведение детальной статистики посетителей веб-сайтов с помощью сервисов Google Analytics и Яндекс.Метрика.
- [ ] Регулярное (1 раза в сутки) резервное копирование исходных кодов, файлов и базы данных.


## <a name='ui'></a>User Interface

- [ ] Поиска по сайту
- [ ] «Хлебные крошки».
      <br>*Пользователь должен знать где он находится, на какой именно странице, в каком разделе.*
      <br>*[Навигационная цепочка](https://ru.wikipedia.org/wiki/%D0%9D%D0%B0%D0%B2%D0%B8%D0%B3%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F_%D1%86%D0%B5%D0%BF%D0%BE%D1%87%D0%BA%D0%B0)*
- [ ] Имя авторизованного пользователя отображается на странице
- [ ] Макет с одной колонкой вместо многоколоночного
- [ ] Персонализация
      <br>*Язык, валюта и прочие специфичные для определенных стран моменты (например, налоги)
      зависят от местоположения пользователь.*
- [ ] Осмысленная регистрация
      <br>*Например, кнопка «Бесплатный период использования» (free trial) лучше, чем просто ссылка «Зарегистрироваться».*
- [ ] Прозрачное ценообразование
      <br>*Цены сразу видны, нет никаких «подводных камней», вроде мелких ценников внизу, звездочек, сносок и т. д.*
- [ ] Отсутствие самопроизвольных изменений на странице
      <br>*Никаких всплывающих окон.*
- [ ] Информация на сайте достоверная
      <br>*Нет битых ссылок, ссылки ведут на соответствующие тематике ресурсы, правильные контакты и т. д.*
- [ ] Ясный и четкий призыв к действию (call for action)
      <br>*Пользователь знает, что делать дальше и какую выгоду это ему принесет. Четко выражена цель и назначение сайта.*
- [ ] Контент написан понятным для пользователя языком, нет перегрузки предложений
      <br>*[read-able.com](http://www.read-able.com)*


## <a name='design'></a>Дизайн

- [ ] Свет падает сверху
- [ ] Соблюдение правил хорошего тона в «Фотошопе»
      <br>*[i-love-psd.ru](http://i-love-psd.ru/)*
      <br>*[photoshopetiquette.com](http://photoshopetiquette.com/)*
      <br>*[andexds.com/projects/checklistui/](http://andexds.com/projects/checklistui/)*
- [ ] Применение единой модульной сетки при проектировании интерфейса веб-сайта
      <br>*Значительно упрощает проектирование интерфейса и последующую вёрстку макета.*
- [ ] Наличие в макетах отдельного слоя с модульной сеткой страницы
      <br>*Следование единой модульной сетке в рамках проекта не только
      увеличит цельность и логичность восприятия сайта, но и многократно
      упростит труд разработчикам.*
- [ ] Представлены различные состояния для интерактивных элементов (кнопок, текстовых полей, ссылок)
      <br>*Обычное (default), посещённое (visited), при наведении мыши (hover), активное (active),
      в фокусе (focus), заблокированное (disabled).*


## <a name='linux'></a>Linux

- [ ] Удалены все ненужные и неиспользуемые пакеты
- [ ] В /etc/apt/sources.list только нужные и проверенные репозитории
- [ ] Используются последние стабильные версии пакетов
- [ ] Установлен и настроен openssh-server
      <br>*[debian.pro/1915](https://debian.pro/1915)*
- [ ] Установлен и настроен fail2ban
      <br>*[debian.pro/179](https://debian.pro/179)*
- [ ] FQDN
      <br>*[debian.pro/1977](https://debian.pro/1977)*
- [ ] Надёжные пароли
      <br>*[debian.pro/2013](https://debian.pro/2013)*


## <a name='etc'></a>Прочее

- [ ] При отправке писем должен быть установлен заголовок List-Unsubscribe
      <br>*[list-unsubscribe.com](http://www.list-unsubscribe.com/)*
