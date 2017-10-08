Техническое задание на вёрстку <br>

Название сайта: LandingPage<br>
Домен: <a href="https://mrblackdevil.github.io/Landing-page/">LandingPage</a><br>
--

Общие технические требования<br>
Кроссбраузерность IE8+<br>
Пиксельная точность для Chrome latest<br>
Верстка должна быть responsive, там есть три макета для разных девайсов. "Mobile first"<br>
Подключить нестандартные шрифты, сами файлы есть в папке fonts. Можно использовать GoogleFonts<br>
Использовать препроцессор на ваш выбор<br>
Применить BEM<br>
Никакого Bootstrap или Pure<br>
Максимально использовать возможности HTML5 и CSS3, но в рамках кроссбраузерности<br>
Применить подход gracefull degradation<br>
Все файлы должны собираться с помощью grunt<br>
На макете есть слайдеры, их нужно сделать с помощью jQuery-плагина<br>
В нижней части макета есть блок картинок (будем называть его плиткой) с заголовком "Discover holiday activity ideas". Их нужно расположить <br>с помощью плагина Masonry, либо с помощью Isotope, либо взять любой другой аналог<br>
Сами картинки нужно взять с помощью ajax-запроса с сервиса или с любого другого сервиса для поиска картинок<br>
После блока "плитки" есть поле поиска. При введении в поле текста и нажатии кнопки "Search partners" нужно отправить запрос на получение картинок с нашего сервиса, и заменить картинки в плитке на новые, соответствующие нашему запросу.<br> Можно использовать шаблонизатор и заново проинициализировать masonry. В качестве текста для каждой картинки можно использовать поле word из ответа сервера
При первой загрузке страницы в плитке должны выводиться случайные картинки
