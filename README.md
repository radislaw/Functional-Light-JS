# Functional-Light JavaScript (книга)

В этой книге рассматриваются основные принципы функционального программирования (ФП), применительно к JavaScript. Но эта книга отличается тем, что мы подходим к этим принципам, не утопая во всей этой тяжелой терминологии. Мы рассмотрим подмножество базовых концепций ФП, которое я называю «Functional-Light Programming» (FLP), и применим его к JavaScript.

**Note:** Despite the word "Light" in the title, I do not consider or recommend this book as a "beginner", "easy", or "intro" book on the topic. This book is rigorous and full of gritty detail; it expects a solid foundation of JS knowledge before diving in. "Light" means limited in scope; instead of being more broad, this book goes much deeper into each topic than you typically find in other FP-JavaScript books.

**Примечание:** Несмотря на слово «Light» в названии, я не рассматриваю и не рекомендую эту книгу в качестве «начальной», «легкой» или «вводной» книги по этой теме. Эта книга является строгой и полной мельчайших деталей; Это подразумевает наличие прочной основы знания JS перед погружением в неё. «Light» означает ограниченный по охвату; Вместо того, чтобы быть более широкой, эта книга проникает гораздо глубже в каждую тему, чем вы обычно находите в других книгах по ФП в JavaScript.

Посмотрим правде в глаза: пока вы не являетесь членом крутого детского клуба по ФП (я нет!), Заявление типа «монада - это просто моноид в категории эндофункторов», просто не означает для нас ничего полезного.

Это не значит, что эти термины бессмысленны или что ФПисты плохие, потому-что используют их. После того, как вы закончите Functional-Light, вы, возможно, захотите изучать ФП более формально, и у вас наверняка будет много возможностей понять, что они означают и почему.

Но я хочу, чтобы вы могли применить некоторые из основ ФП к вашему JavaScript *сейчас*, потому что я считаю, что это поможет вам писать лучший, более *разумный* код.

**Чтобы узнать больше о мотивах и перспективах этой книги, ознакомьтесь с [введением](preface.md).**

## Книга

[Оглавление](toc.md)

* [Предисловие](foreword.md) (от [Brian Lonsdorf aka "Prof Frisby"](https://twitter.com/DrBoolean))
* [Введение](preface.md)
* [Глава 1: Почему функциональное программирование?](ch1.md)
* [Глава 2: Природа функций](ch2.md)
* [Глава 3: Managing Function Inputs](ch3.md)
* [Глава 4: Composing Functions](ch4.md)
* [Глава 5: Reducing Side Effects](ch5.md)
* [Глава 6: Value Immutability](ch6.md)
* [Глава 7: Closure vs Object](ch7.md)
* [Глава 8: Рекурсия](ch8.md)
* [Глава 9: List Operations](ch9.md)
* [Глава 10: Functional Async](ch10.md)
* [Глава 11: Putting It All together](ch11.md)
* [Приложение A: Transducing](apA.md)
* [Приложение B: The Humble Monad](apB.md)
* [Приложение C: FP Libraries](apC.md)

## Publishing
## Издательство

Я сам публикую эту книгу, скорее всего, в цифровой форме [на Leanpub](https://leanpub.com/fljs/). Я также попытаюсь выработать вариант для продажи копий печатных книг, но эта часть все еще остается неопределенной.

I'm self-publishing this book, most likely digitally [on Leanpub](https://leanpub.com/fljs/). I'll also be trying to work out an option to sell print book copies, but that part is still uncertain.

Если вы хотите внести финансовый вклад в работу (или любую другую мою работу OSS), кроме покупки книг, у меня есть [patreon] (https://www.patreon.com/getify), что я всегда буду оцените свою щедрость.


If you'd like to contribute financially towards the effort (or any of my other OSS work) aside from purchasing the books, I do have a [patreon](https://www.patreon.com/getify) that I would always appreciate your generosity towards.

<a href="https://www.patreon.com/getify">[![patreon.png](https://s11.postimg.org/axpzguh77/patreon.png)](https://www.patreon.com/getify)</a>

## Персональный тренинг

Содержание этой книги в значительной степени зависит от учебного семинара с тем же названием, который я преподаю профессионально (как в публичном, так и в частном корпоративном формате).

Если вам нравится этот контент и вы хотите связаться со мной относительно проведения обучения по этой или другим различным темам по JS / HTML5 / Node.js, пожалуйста, обратитесь ко мне через любой из перечисленных здесь каналов:

[http://getify.me](http://getify.me)

## Oнлайн видео тренинг

Также у меня есть несколько учебных курсов по JS, доступных в формате видео по запросу. Я преподаю курсы на [Frontend Masters](https://FrontendMasters.com), такие как семинар [Functional-Lite JS](https://frontendmasters.com/courses/functional-js-lite/). Некоторые из этих курсов также доступны на сайте [PluralSight](https://www.pluralsight.com/search?q=kyle%20simpson&categories=all).

## Contributions

Любые вклады, которые вы делаете для этих усилий **, конечно, очень ценятся **.
Any contributions you make to this effort **are of course greatly appreciated**.

Но **ПОЖАЛУЙСТА** внимательно прочитайте [Рекомендации по взносам] (CONTRIBUTING.md) перед подачей PR.

But **PLEASE** read the [Contributions Guidelines](CONTRIBUTING.md) carefully before submitting a PR.

## Лицензия и авторские права

Все материалы здесь (c) 2016-2017 Kyle Simpson.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />Эта работа лицензируется в соответствии с <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License</a>.
