# Учебный проект по анализу данных 2023

**много транспорта и кода:)**

![это электро...](https://github.com/ankp0/andan-2023-project/blob/main/%D0%B2%D0%BE%D0%BB%D0%B3%D0%B0.jpg)

## План действий
<p>Итак, вашему вниманию представляется учебный проект по анализу данных о ДТП в Москве (и немножко в Московской области) за 2022 год (Анализ данных на Python, ФЭН ВШЭ, 2 курс).</p>
<p>Основной целью было глянуть на закономерности, которые возникли (или не возникли...) в количестве ДТП и факторах, которые на него повлияли. Данные были грязноватые (вопросы к реальному миру и тем, кто занимался сбором...), но анализ таки проведён был.</p>
<p>Была рассмотрена куча категориальных признаков (районы, округа, погода, время суток, тип ДТП и так далее и тому подобное), выявлены какие-то закономерности, что-то проверено и что-то обучено. Приятного просмотра :)</p>
<ul>
<li><b>Дано:</b> датасет с ДТП по Москве и Московской области за 2022 год (в районе 7.5к наблюдений и 40 признаков), желание попытаться в работу с реальными данными</li>
<li><b>На выходе:</b> немного EDA и визуализаций, немного гипотез и машинного обучения, попытка засчитана</li>

## Важные ссылочки, замечания и соображения
- Из соображений конфиденциальности исходного датасета тут не будет, но до данных, в теории, можно докопаться самостоятлеьно на сайте ГИБДД из вкладки [показатели состояния безопасности дорожного движения](http://stat.gibdd.ru/) (**но это неточно :)**)
- Блокнот с кодом разбит на две глобальные смысловые части - **обработка данных, EDA, визуализации и создание новых признаков** [(лежит тут)](https://github.com/ankp0/andan-2023-project/blob/main/eda.ipynb) и **проверка гипотез с машинным обучением** [(а оно тут)](https://github.com/ankp0/andan-2023-project/blob/main/hypothesis_ML.ipynb)
  
