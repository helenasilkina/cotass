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

Максимальный поток в ненаправленном графе: 
<a href="https://www.youtube.com/watch?v=uRQAl7oZ0cQ&index=6&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 1</a>, 
<a href="https://www.youtube.com/watch?v=2MvMKhdhgTQ&index=7&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 2</a>, 
<a href="https://www.youtube.com/watch?v=mPy8ZUMfiSA&index=8&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 3</a>, 
<a href="https://www.youtube.com/watch?v=PiAFl2sJ8B0&index=9&list=PLuWypj7F_mQlIBhQwfb8qgRjI-qZuJx1U">часть 4</a>

На спецсеминаре Максим Бабенко рассказывал о максимальных потоках в ненаправленных графах. Рассказ был построен на основе статей Гольдберга-Рао и Каргера-Левина: <a href="http://citeseer.ist.psu.edu/viewdoc/summary?doi=10.1.1.52.3087">Finding Maximum Flows in Undirected Graphs Seems Easier than Bipartite Matching by David R. Karger, Matthew S. Levine</a>; 
<a href="http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.50.116">Flows in Undirected Unit Capacity Networks by Andrew V. Goldberg, Satish Rao</a>

Источник: <a href="https://cotass.wordpress.com/2011/04/15/%D0%B2%D0%B8%D0%B4%D0%B5%D0%BE-%D1%81%D0%BF%D0%B5%D1%86%D1%81%D0%B5%D0%BC%D0%B8%D0%BD%D0%B0%D1%80-6-04-%D0%B8-%D1%81%D0%BF%D0%B5%D1%86%D0%BA%D1%83%D1%80%D1%81-13-04/">cotass</a>
