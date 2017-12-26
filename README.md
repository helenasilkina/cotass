Видео с блога спецсеминара по комбинаторной оптимизации и теории алгоритмов под руководством Максима Бабенко:

<a href="https://www.youtube.com/watch?v=eYnu8spEPws">Поиск путей из одной вершины в другую с помощью случайных блужданий в графе</a>

Были рассказаны алгоритмы поиска путей из одной вершины графа в другую и нахождения выполняющего набора для 2-SAT с помощью метода случайных блужданий на графе.
Источник: <a href="https://cotass.wordpress.com/2011/03/25/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BF%D0%BE-%D0%BF%D1%80%D0%B8%D0%B1%D0%BB%D0%B8%D0%B6%D0%B5%D0%BD%D0%BD%D1%8B%D0%BC-%D0%B8-%D0%B2%D0%B5%D1%80%D0%BE/">cotass</a>

<a href="https://www.youtube.com/watch?v=PW1ecpUkG7A&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=2">Geometry of binary search trees </a>

Ваня Пузыревский рассказывает про статью Эрика Дамейна 2009 года - "Geometry of BST". <a href="https://www.mindmeister.com/87191212/geometry-of-bst">Mind-Map</a>

Одна из давних нерешенных задач TCS — это задача о динамической оптимальности исполнения последовательности запросов к бинарному дереву поиска. Пусть есть последовательность запросов S, которая задается алгоритму; алгоритм на каждом шаге ищет запрашиваемый ключ в дереве и, возможно, как-то его перестраивает. Задача состоит в том, чтобы построить алгоритм, наиболее оптимально исполняющий приходящие запросы (в случае неизвестного априори S — задача динамическая; в случае известного — статическая). Алгоритм, который был бы доказуемо оптимален в общем случае, пока что неизвестен.

В статье «Geometry of binary search trees» Эрика Дамейна 2009 года описывается интересная связь между исполнением запросов к дереву и специальными наборами точек на плоскости. Оказывается, что любое выполнение запросов можно закодировать древовидным набором точек на плоскости. Верно и обратное: по любому древовидному набору точек можно построить восстановить корректное исполнение запросов. Такая (неожиданная) геометрическая интерпретация позволяет иначе взглянуть на проблему, заметить очевидные геометрически, но не очевидные с точки зрения деревьев факты.
Источник: <a href="https://cotass.wordpress.com/2011/03/27/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d0%b4%d0%be%d0%ba%d0%bb%d0%b0%d0%b4-%d0%b8%d0%b2%d0%b0%d0%bd%d0%b0-%d0%bf%d1%83%d0%b7%d1%8b%d1%80%d0%b5%d0%b2%d1%81%d0%ba%d0%be%d0%b3%d0%be-23-03-11/">cotass</a>

<a href="https://www.youtube.com/watch?v=EQGTx10Y4jY&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=3">Приближенное вычисление количества совершенных паросочетаний в двудольном графе</a>

Было закончено доказательство теоремы о связи случайных блужданий на графе и оценке эффективных напряжений в некоторой сети. Кроме того, была рассказана идея приближенного вычисления количества совершенных паросочетаний в двудольном графе с долями одинаковой мощности (эта задача принадлежит #P, поэтому полиномиального алгоритма, вычисляющего точное количество, не существует).
Источник: <a href="https://cotass.wordpress.com/2011/04/01/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bf%d0%be-%d0%bf%d1%80%d0%b8%d0%b1%d0%bb%d0%b8%d0%b6%d0%b5%d0%bd%d0%bd%d1%8b%d0%bc-%d0%b8-%d0%b2%d0%b5%d1%80%d0%be-2/">cotass</a>

<a href="https://www.youtube.com/watch?v=uiqzYu8-8Nc&index=4&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Эффективная реализация хэш-таблицы с параллельным доступом</a>

Эффективная реализация хэш-таблицы с параллельным доступом — очень интересная с точки зрения практики задача. Практически все подходы, основанные на блокирующей синхронизации, при большом количестве потоков страдают от больших задержек и инверсии приоритетов при неудачном перехвате потока шедулером.

В 2006 году вышла статья Ори Шалева и Нира Шавита, в которой описана новая конструкция свободной от блокировок (lock-free) расширяемой хэш-таблицы на основе lock-free связного списка. По сути, эта структура данных представляет из себя отсортированный список со skip pointer’ами, дающими гарантии O(1) времени в среднем на все операции хэш-таблицы, причём эти гарантии остаются верными даже при довольно сильных предположениях о нечестности шедулера.
Исходник: <a href="https://cotass.wordpress.com/2011/04/02/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d0%b4%d0%be%d0%ba%d0%bb%d0%b0%d0%b4-%d0%b0%d0%bb%d0%b5%d0%ba%d1%81%d0%b0%d0%bd%d0%b4%d1%80%d0%b0-%d1%85%d0%b0%d1%80%d0%b8%d1%82%d0%be%d0%bd%d0%be%d0%b2%d0%b0-30-03-11/">cotass</a>


<a href="https://www.youtube.com/watch?v=iwbVYhZTRk0&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=5">Поиск совершенного паросочетания в произвольном графе</a> 

Было рассказано о том, как можно свести задачу о нахождении совершенного паросочетания в произвольном графе к задаче вычисления детерминанта специальной матрицы. Также было рассказано о locality sensitive hashing и о применении этой техники в нескольких специальных случаях.
Источник: <a href="https://cotass.wordpress.com/2011/04/15/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D1%81%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80-6-04-%D0%B8-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-13-04/">cotass</a>

<a href="https://www.youtube.com/watch?v=uRQAl7oZ0cQ&index=6&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Максимальный поток в ненаправленном графе часть 1</a>, 
<a href="https://www.youtube.com/watch?v=2MvMKhdhgTQ&index=7&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 2</a>, 
<a href="https://www.youtube.com/watch?v=mPy8ZUMfiSA&index=8&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 3</a>, 
<a href="https://www.youtube.com/watch?v=PiAFl2sJ8B0&index=9&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 4</a>

На спецсеминаре Максим Бабенко рассказывал о максимальных потоках в ненаправленных графах. Рассказ был построен на основе статей Гольдберга-Рао и Каргера-Левина: <a href="http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.52.3087">Finding Maximum Flows in Undirected Graphs Seems Easier than Bipartite Matching by David R. Karger, Matthew S. Levine</a>; 
<a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.50.116">Flows in Undirected Unit Capacity Networks by Andrew V. Goldberg, Satish Rao</a>
Источник: <a href="https://cotass.wordpress.com/2011/04/15/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D1%81%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80-6-04-%D0%B8-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-13-04/">cotass</a>

<a href="https://www.youtube.com/watch?v=C0twLZomNlk">Минимальные разрезы в графах и кактусы</a> 

На спецсеминаре Руслан Савченко рассказал о статье Tamás Fleiner и András Frank 2009 года о представлении минимальных разрезов в произвольном графе минимальными разрезами в кактусе (графе, в котором каждое ребро принадлежит единственному простому циклу). Источник: <a href="https://cotass.wordpress.com/2011/04/24/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d0%bc%d0%b8%d0%bd%d0%b8%d0%bc%d0%b0%d0%bb%d1%8c%d0%bd%d1%8b%d0%b5-%d1%80%d0%b0%d0%b7%d1%80%d0%b5%d0%b7%d1%8b-%d0%b2-%d0%b3%d1%80%d0%b0%d1%84%d0%b0%d1%85-%d0%b8-%d0%ba/">Cotass</a>

<a href="https://www.youtube.com/watch?v=MKJfiVwDLns&index=11&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Алгоритм нахождения высокочастотных элементов в последовательности</a>

На спецкурсе по приближенным и вероятностым алгоритмам было рассказано об алгоритме, который за два прохода по последовательности вычисляет все ее элементы, встречающиеся хотя бы nk раз, где k — некоторое фиксированное число, а n — длина последовательности.  Несмотря на простоту алгоритма, придуман он был совсем недавно.

<a href="https://www.youtube.com/watch?v=LCgBiPQ4IQ8&t=835s&index=12&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Приближенный алгоритм для задачи scheduling</a>

Максим Бабенко рассказал о задаче scheduling и привел приближенный алгоритм для нее (с approx. ratio = 2). Источник: <a href="https://cotass.wordpress.com/2011/05/16/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-11-%D0%BC%D0%B0%D1%8F/">Cotass</a>

<a href="https://www.youtube.com/watch?v=43vldP9em3E&t=1523s&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=13">Поиск оптимальных бранчингов и арборисценций в направленных графах</a>

На спецсеминаре состоялся доклад Алексея Черепанова. В нем рассказывается про эффективное решение задач поиска оптимальных бранчингов и арборисценций в направленных графах (аналог остовных деревьев в ненаправленных графах). Были изложены алгоритмы для решения этой задачи за время O(m + n log n), также был рассказан алгоритм для эффективного поиска k/(k + 1) приближения. Источник: <a href="https://cotass.wordpress.com/2011/09/26/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-21-09-2011-%d0%b8-%d1%81%d0%bf%d0%b5/">Cotass</a>

<a href="https://www.youtube.com/watch?v=dhgQqdiC2Wo&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=14">Паросочетания в планарных графах </a>
Максим Бабенко рассказывает про задачу подсчета количества совершенных паросочетаний в различных графах. В частности, был изложен полиномиальный алгоритм для grid-графов. Источник: <a href="https://cotass.wordpress.com/2011/09/26/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-21-09-2011-%D0%B8-%D1%81%D0%BF%D0%B5/">Cotass</a>

<a href="https://www.youtube.com/watch?v=JJ56G_ec6H8&index=15&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=1s">Поиск подграфа максимальной плотности</a>

На спецсеминаре состоялся доклад Игната Колесниченко. На нем было рассказано про задачу поиска подграфа максимальной плотности и её вариации. В общем виде задача формулирается так: дан граф G=(V, E) и целое число k. Требуется найти такое подмножество вершин S размера k, что величина |E(S)|/|S| максимальна. На докладе был рассказан способ сведения данной задаче к задаче поиска наилучшего кластера размера k. Результат совершенно новый и открывает интересные возможности для решения исходной задачи. <a href="https://video.yandex.ru/users/sverx-novay/view/6/">Cotass</a>

<a href="https://www.youtube.com/watch?v=TP1QNiIDOMo&index=16&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=19s">Сепараторы в планарных графах и их применения </a>

На спецкурсе Максим Бабенко рассказывал про сепараторы в планарных графах и их применения. В частности, был рассказан алгоритм для поиска наибольшего независимого множества вершин в планарном графе и алгоритм для поиска сепаратора. <a href="https://cotass.wordpress.com/2011/10/09/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-2/">Cotass</a>

<a href="https://www.youtube.com/watch?v=SLdHShombEg&index=17&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=871s">Задача о минимальном сбалансированном разрезе </a>

На спецсеминаре состоялся доклад Ильи Разенштейна «Теоретические и практические аспекты задачи о минимальном сбалансированном разрезе». 

Рассмотрим следующую задачу. Пусть у нас есть ненаправленный граф с четным числом вершин. Мы хотим разбить его вершины на две равные по размеру части так, чтобы количество ребер между ними было минимальным. Эта задача NP-трудная. 

В докладе будет представлен комбинаторный переборный алгоритм для задачи о минимальном сбалансированном разрезе, который работает хорошо, если ответ на задачу небольшой (при этом, сам граф может быть очень большим). Интересные примеры графов из этого класса включают в себя дорожные сети, VLSI схемы и триангуляции. Наибольший интересный граф, который точно удалось решить — это карта северо-запада США (1.2 миллиона вершин). <a href="https://cotass.wordpress.com/2011/10/09/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-2/">Cotass</a>

<a href="https://www.youtube.com/watch?v=AUnG61z5vB4&t=380s&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=18">Анализ Фурье и его применение к задачам тестирования свойств булевых функций</a>

На спецсеминаре состоялся доклад Ильи Разенштейна. Илья рассказывает про анализ Фурье и его применение к задачам тестирования свойств булевых функций. Из доклада вы можете узнать про эффективный алгоритм, который используя всего три запроса к булевой функции с большой вероятностью определяет является ли она линейной. Данная задача нужна в доказательстве PCP-теоремы.

Также был рассказан алгоритм для тестирования булевой функции на принадлежность к классу диктаторов и другие интересные применения анализа Фурье. <a href="https://cotass.wordpress.com/2011/10/15/181/">Cotass</a>

<a href="https://www.youtube.com/watch?v=au6H9nKiv2g&index=19&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=5s">Про анализ Фурье: теоремы Фрейдгута и Канна-Калаи-Линиала</a>

На спецсеминаре состоялся Илья Разенштейн продолжил свой доклад про анализ Фурье. На этот раз была доказаны две теоремы: Фрейдгута и Канна-Калаи-Линиала. Первая теорема утверждает, что булевы функции с маленькой чувствительностью близки к функциям с малым числом существенных переменных (обобщение изопериметрического неравенства на булевом кубе). Вторая теорема утверждает, что у сбалансированных булевых функций найдется влиятельная переменная.<a href="https://cotass.wordpress.com/2011/10/23/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-3/">Cotass</a>

<a href="https://www.youtube.com/watch?v=xLUjep4fqB8&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=2740s&index=20">Эффективный алгоритм для поиска циклических сепараторов в планарных графах</a>

На спецкурсе Максим Бабенко продолжает рассказ про планарные графы. На этом занятии был рассказан эффективный алгоритм для поиска циклических сепараторов в планарных графах. Свойство цикличности сепаратора позволяет решать некоторые задачи на планарных графах, которые не решаются с использованием сепараторов общего вида. Также бы рассказан алгоритм для поиска кратчайших путей в планарных графах, более эффективный чем алгоритм Форда-Беллмана в случае произвольных весов ребер.
<a href="https://cotass.wordpress.com/2011/10/15/181/">Cotass</a>

<a href="https://www.youtube.com/watch?v=FjZU3rDdMqY&index=21&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Эффективный поиск кратчайших путей в планарных графах</a>

На спецкурсе было рассказано про эффективный поиск кратчайших путей в планарных графах. Максим рассказал алгоритм, который позволяет выполнять поиск всех кратчайших путей из каждой вершины внешней грани планарного графа за общее время O(n  \log n ). Результат может показаться удивительным, так как величина ответа в такой задаче может быть порядка O(n^2).
Источник:<a href="https://cotass.wordpress.com/2011/10/30/видео-спецкурс-максима-бабенко-и-обзо/"> Cotass</a>

<a href="https://www.youtube.com/watch?v=iDgrZwrPknE&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=22">Поиск максимального вершинного покрытия для планарных графов</a>

На спецкурсе было рассказано про графы ограниченной путевой ширины и ограниченной древесной ширины. Известно, что для таких графов многие NP-трудные задачи делаются за полиномиальное время. Также на основе введенных определений был рассказан эффективный алгоритм поиска максимального вершинного покрытия для планарных графов. Источник: <a href="https://cotass.wordpress.com/2011/10/23/видео-спецкурс-максима-бабенко-и-докл-3/">cotass</a>

<a href="https://www.youtube.com/watch?v=bXMpieOpEqA&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=23&t=35s">Алгоритмы во внешней памяти</a>

В докладе было рассказано про модель вычислений во внешней памяти, про эффективные алгоритмы сортировки большого объема данных и про обход в ширину больших графов (например веб-графа, в котором сотни миллиардов вершин и ребер). Стоит отметить, что данные алгоритмы разительно отличаются от их аналогов во внутренней памяти.

<a href="https://www.youtube.com/watch?v=Srcem4_2Aa0&t=1016s&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=24">Вероятностный алгоритм поиска минимального разреза в планарном графе в невзвешенном случае</a>

На спецкурсе было рассказано про задачу поиска минимальных разрезов и циклов в планарных графах. Был рассказан достаточно красивый вероятностный алгоритм поиска минимального разреза в планарном графе в невзвешенном случае, работающий за линейное время. Это достаточно новый результат, использующий технику Color Coding (Zwick, 1994).
Также был рассказан алгоритм для поиска минимального разреза для случая взвешенного графа. Этот алгоритм использует рассказанную ранее технику поиска циклических сепараторов в планарных графах. Источник: <a href="https://cotass.wordpress.com/2011/11/06/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-4/">cotass</a>

<a href="https://www.youtube.com/watch?v=4B4qLg7t9IU&index=25&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=3462s">Поиск кратчайших путей в полном графе</a>

На спецкурсе рассказывалось про задачу поиска кратчайших путей в полном графе при условии, что матрица расстояний является матрицей Монжа. Оказывается, что в этом случае можно модифицировать алгоритм Дейкстры и алгоритм Беллмана-Форда. Источник: <a href="https://cotass.wordpress.com/2011/11/13/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-5/">cotass</a>

<a href="https://www.youtube.com/watch?v=PYojH-00XAA&index=26&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Задача определения похожести двух строк</a>

На спецсеминаре состоялся доклад Александра Тискина. Основной темой доклада была задача определения похожести двух строк. Для решения этой задачи необходимо эффективно искать LCS (поиск наибольшей общей подпоследовательности) между некоторой строкой a и произвольной подстрокой другой строки b. Оказывается, что задачу можно решать столь же эффективно, как и просто поиск LCS двух строк. Для этого вводятся интересные алгебраические объекты, называемые матрицами водорослей со структурой моноида на них (структура задается операцией тропического умножения). <a href="https://cotass.wordpress.com/2011/11/20/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-6/">Cotass</a>

<a href="https://www.youtube.com/watch?v=ERmIw8ltYcY&index=27&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&t=21s">Exchange и некоторые алгоритмы, используемые в биржевых роботах</a>

На докладе профессора Мичиганского универстите, Кирилла Ванинского было рассказано про Exchange и некоторые алгоритмы, используемые в биржевых роботах. <a href="https://cotass.wordpress.com/2011/11/24/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d0%b4%d0%be%d0%ba%d0%bb%d0%b0%d0%b4-%d0%ba%d0%b8%d1%80%d0%b8%d0%bb%d0%bb%d0%b0-%d0%b2%d0%b0%d0%bd%d0%b8%d0%bd%d1%81%d0%ba%d0%be%d0%b3%d0%be-23-11-2011/">Cotass</a>

<a href="https://www.youtube.com/watch?v=das1x_ntedU&t=197s&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=28">Укладка планарных графов, алгоритм D. Eppstein</a>

На спецкурсе было рассказано про укладки планарных графов. Обычно под укладкой графа понимают не набор точек и отрезков на плоскости, а некоторую структуру, заданную на графе. Говорят, что у графа указана комбинаторной укладка, если в каждой вершине задан линейный циклический порядок на инцидентных ей ребрах. Зная комбинаторную укладку, можно реализовать большинство эффективных алгоритмов на планарных графах. Основная тема данного занятия — это алгоритм D. Eppstein, позволяющий по комбинаторной укладке графа построить его укладку в единичную решетку, линейную по размеру графа. Алгоритм очень красивый и не требует каких-либо дополнительных знаний. Здесь можно посмотреть <a href="http://cl.ly/3t0M0m0U3J3r0C1f2A3W">слайды про этот алгоритм</a>
<a href="https://cotass.wordpress.com/2011/12/03/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-7/">Cotass</a>

<a href="https://www.youtube.com/edit?video_referrer=watch&video_id=R3OyjfuGgb4">Алгоритмы спарсификации графов, сохраняющие величины s-t разрезов, часть 1</a>

На спецсеминаре Илья Разенштейн рассказал про алгоритмы спарсификации графов, сохраняющие величины s-t разрезов. Под  спарсификацией понимается удаление ребер графа. Очевидно, что при удалении любого ребра для некоторых s и t величина потока изменится, поэтому сохранить величины всех потоков не получится. Однако, можно выбрать некоторое E и удалить значительное количество ребер, так, что относительные величины всех s-t потоков изменятся не более чем на E. Илья рассказал теорему Бенезура-Каргера. Также в долкаде было разобрано несколько простых, но крайне полезных утверждений: лемма Каргера-Штайна и Теорема Чернова.
<a href="https://cotass.wordpress.com/2012/03/11/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-9/">Cotass</a>

<a href="https://www.youtube.com/watch?v=1DLk-7dK-Oo&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=31">Алгоритмы спарсификации графов, сохраняющие величины s-t разрезов, часть 2</a>

Продолжение доклада Ильи Разенштейна про алгоритмы спарсификации графы, сохраняющие величины s-t разрезов. Под  спарсификацией понимается удаление ребер графа. Очевидно, что при удалении любого ребра для некоторых s и t величина потока изменится, поэтому сохранить величины всех потоков не получится. Однако, можно выбрать некоторое E и удалить значительное количество ребер, так, что относительные величины всех s-t потоков изменятся не более чем на E. Илья рассказал теорему Бенезура-Каргера. Также в долкаде было разобрано несколько простых, но крайне полезных утверждений: лемма Каргера-Штайна и Теорема Чернова.
<a href="https://cotass.wordpress.com/2012/03/11/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-10/">Cotass</a>

<a href="https://www.youtube.com/watch?v=pWzTvauzSHw&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=32">B-деревья и их разновидности во внешней памяти</a>

На данном семинаре разбирались B-деревья и их разновидности. Основная их отличительная черта — большая степень ветвления, позволяющая радикально понизить высоту дерева, а значит уменьшить количество случайных обращений к диску. И все же B-деревья не способны эффективно решать задачи, в которых количество операций со структурой данных велико. Например, невозможно эффективно отсортировать данные во внешней памяти с помощью B-дерева. На помощь приходит batching: нужно запоминать вставки, обрабатывая их не поотдельности, а группами. На этой идее и построено буферирозованное дерево, изучение которого было начато на этом занятии.
<a href="https://cotass.wordpress.com/2012/03/11/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-10/">Cotass</a>

<a href="https://www.youtube.com/watch?v=FaKnYm8UI6s&index=33&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Поиск статистик в потоке данных (Data Streaming Algorithms)</a>

На спецсеминаре состоялся доклад Игната Колесниченко про алгоритмы поиска статистик в потоке данных (Data Streaming Algorithms). Это область алгоритмов для работы с большими объемами данных при условии, что используется небольшое количество памяти. В докладе было подробно рассказано про модель вычислений, разобраны основные задачи, появляющиеся в данной области. Подробно была разобрана задача поиска медианы в потоке чисел. В частности был рассказан алгоритм Манро-Патерсона для поиска медианы за несколько проходов по потоку. Также была рассказана эффективная (рандомизированная) структура данных для поддержания массива счетчиков, под названием Count-Min.
<a href="https://cotass.wordpress.com/2012/03/11/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-11/">Cotass</a>

<a href="https://www.youtube.com/watch?v=lY83AN4Q_gY&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U&index=34">Модель вычислений во внешней памяти</a>

На первой лекции была разобрана модель вычислений во внешней памяти. Данная модель приближена к реальному устройству компьютера с точки зрения работы с памятью, но при этом не учитывает процессорное время. Также были рассказаны простейшие алгоритмы для работы с данными во внешней памяти: последовательное чтение данных и сортировка. 
<a href="https://cotass.wordpress.com/2012/02/19/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-8/">Cotass</a>

<a href="https://www.youtube.com/watch?v=o0UrkAMDl8M&index=35&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Buffered Repository Tree во внешней памяти</a>

На спецкурсе мы закончили анализ буферизованного дерева, и выяснили, как с его помощью сортировать данные. Также было введено понятие offline-поиска и удаления, а разобрана их реализация на буферизованном дереве. Наконец, на основе буферизованного дерева оказалось возможным реализовать приоритетную очередь во внешней памяти, которая способна в режиме online искать (и удалять) минимум существенно быстрее, чем обычное B-дерево. Далее мы перешли к алгоритмам и структурам данных для работы с графами. Типичный алгоритм на графах — обход в глубину — оказывается неэффективным во внешней памяти. А именно, он требует порядка V+E случайных обращений к диску. Наша цель — уменьшить второе слагаемое (как уменьшать первое никто пока не знает). Для этого нам понадобится новая структура данных, называемая Buffered Repository Tree.
<a href="https://cotass.wordpress.com/2012/03/11/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-11/">Источник</a>

<a href="https://www.youtube.com/watch?v=a1PorrG5cBY&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Модификация B-деревьев во внешней памяти под названием BRT</a>

На спекурсе было рассказано про модификацию B-деревьев во внешней памяти под названием BRT. Эта структура данных позволяет эффективно отвечать на запрос find в онлайн режиме, а также производить вставки и удаления. Далее было рассказано как эффективно обходить графы во внешней памяти: поиск в глубину (DFS) и поиск в ширину (BFS). Подразумевается, что количество вершин в графе больше, чем количество имеющейся оперативной памяти. Задача обхода в такой постановке считается сложной, так как наивная реализация обоих алгоритмов требует O(E) seek-ов. Однако, используя BRT можно решить DFS за время O((V + E/B) \log E/B). Решить BFS также можно быстрее чем за O(E).<a href="https://cotass.wordpress.com/2012/03/15/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%B4%D0%BE%D0%BA%D0%BB-12/">Источник</a>

<a href="https://www.youtube.com/watch?v=kHfKoAAJEIM&index=37&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Эффективный обход разреженного графа во внешней памяти</a>

Как было выяснено раньше, эффективный обход разреженного графа во внешней памяти представляет собой сложную задачу. Действительно, для каждой посещаемой вершины приходится читать с диска список выходящих из нее ребер, что неизбежно влечет за собой хотя бы одну операцию ввода-вывода. Тем самым, суммарно любой стандартный метод потребует не менее V таковых операций. Мельхорну и Мейеру удалось ускорить алгоритм, разбив граф на части и рассматривая множество ребер в тех частях, которые в настоящий момент задевает «фронт волны BFS». Данный прием носит название «hotlist», он был подробно разобран и проанализирован на занятии спецкурса.<a href="https://cotass.wordpress.com/2012/03/26/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-%D0%BC%D0%B0%D0%BA%D1%81%D0%B8%D0%BC%D0%B0-%D0%B1%D0%B0%D0%B1%D0%B5%D0%BD%D0%BA%D0%BE-%D0%B8-%D0%BF%D1%80%D0%BE%D0%B4/">Источник</a>

<a href="https://www.youtube.com/watch?v=klJiDyV3wPM&index=38&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Динамическая задача транзитивного замыкания графа</a>

На спецсеминаре состоялся доклад Ивана Пузыревского, на котором разбиралась задача поиска транзитивного замыкания графа в динамическом случае. Задача ставится следующим образом: дан ориентированный граф G = (V, A) без циклов и набор запросов, сохраняющий ацикличность. Запросы бывают трех типов: добавить ребро, удалить ребро и спросить есть ли путь между вершинами u и v (причем на последний запрос требуется отвечать онлайн). На семинаре было разобрано два алгоритма для решения этой задачи, один из которых рандомизированный.
<a href="https://cotass.wordpress.com/2012/03/15/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-12/">Источник</a>

<a href="https://www.youtube.com/watch?v=pTOZrsRGhzM&index=40&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">Алгоритм Борувки во внешней памяти</a>

На этом занятии спецкурса были изучены подробности реализации алгоритм Борувки во внешней памяти. Для того, чтобы эффективно выделять компоненты связности в стягиваемом лесе мы воспользуемся идеей эйлерового обхода и применим алгоритм ранжирования списка. Таким образом будет достигнута сложность O(Sort(E) \log V). Существует два способа еще ее уменьшить. Один, приводящий к уменьшению числа, стоящего под логарифмом, основан на переключении (по достижении определенной плотности графа) на алгоритм Прима во внешней памяти. Другой, более интересный и приводящий к замене одинарного логарифма на двойной, использует идею спарсификации.
<a href="https://cotass.wordpress.com/2012/04/02/%d0%b2%d0%b8%d0%b4%d0%b5%d0%be-%d1%81%d0%bf%d0%b5%d1%86%d0%ba%d1%83%d1%80%d1%81-%d0%bc%d0%b0%d0%ba%d1%81%d0%b8%d0%bc%d0%b0-%d0%b1%d0%b0%d0%b1%d0%b5%d0%bd%d0%ba%d0%be-%d0%b8-%d0%b4%d0%be%d0%ba%d0%bb-13/">Источник</a>

