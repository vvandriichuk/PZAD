# ПЗАД: "Прикладные задачи анализа данных"

* Курс на факультете ВМК, МГУ имени М.В. Ломоносова
* для магистров: 517 группа (каф. математических методов прогнозирования) + спецкурс
* лектор: [Александр Дьяконов](https://dyakonov.org/ag/)

# регистрация на спецкурс ЗАВЕРШЕНА
Магистры ВМК МГУ могут посещать этот курс как спецкурс, для этого надо до 11.09.20 (первая лекция) зарегистрироваться.

**Важно:** курс читается по 2 занятия в неделю, есть лекции и семинары(!), даётся много нетривиальных заданий, прохождение курса очень трудоёмко. Читаться будет, скорее всего, по пятницам в 14:35.

Надо зарегистрироваться на классруме и войти в курс (необходимо иметь аккаунт на Google).

Дальше следите за заданиями через классрум - в день первой лекции 11.09.2020 Вам будет дана ссылка на неё, а также форма для окончательной регистрации.


### оценки

тут будет список группы с оценками

### слайды лекций

| тема | программа |
| :-- | :-- |
| [**Введение**](./2020/PZAD2020_000intro_05n.pdf) 11.09.2020 | Вводная лекция|
| [**Оценки среднего, вероятности и плотности; весовые схемы**](./2020/PZAD2020_011probweights_07n.pdf) 11.09.2020 | Понятие «среднее»: разные формализации, полюсы/минусы, практика. Среднее арифметическое. Медиана. многомерная медиана.Многомерная медиана как результат итерационного процесса. Среднее как решение оптимизационной задачи. Оценка минимального контраста. Среднее для номинальных признаков? Среднее по А.Н.Колмогорову. Тропическое среднее. Оценка вероятности как среднего: сглаживание Лапласа и весовые схемы. case: некорректности при вычислении вероятности.|
| [**CASE: Прогнозирование визитов покупателей супермаркетов и сумм их покупок**](./2020/PZAD2020_012caseclients_04n.pdf) 18.09.2020 | Постановка задачи. Предположения метода. Оценки вероятности / весовые схемы. Оценки плотности / весовые схемы. «Состыковка» алгоритмов.|
| [**CASE: задача о пробках**](./2020/PZAD2020_013traffic_02n.pdf ) 18.09.2020 | Постановка задачи. Двухмерное усреднение. Особенности данных. Специальное усреднение.|
| [**Искусство визуализации (часть 1 - историческая)**](./2020/PZAD2020_021vishistory_04.pdf) 18.09.2020 | Обоснование визуализации: квартет Энскомба. Цели визуализации. История анализа данных и инфографики: Джозеф Пристли, Уильям Плейфэр, Шарль Жозеф Минар, Флоренс Найтингейл, Уильям Дюбуа, Джон Сноу. Примеры плохих визуализаций: 3D-графика, нелинейные сравнения, диаграммы-пироги (pie). Максимизация «Data-Ink». Визуальные обманы. Визуализация для профессионала. Правило минимализма. Правило использования разнообразных средств. Рекомендации по выбору масштаба графиков и шкалы, пояснительного текста, цвета и стиля изображений. Табличные данные.|
| **Игра "Что изображено?"** слайды не выкладываются 25.09.2020 | |
| [**Искусство визуализации (часть 2 - одномерный анализ)**](./2020/PZAD2020_022visunivar_04.pdf) 25.09.2020 | Описательные статистики: среднее, характерные элементы, разброс значений, абсолютные вариации, относительные вариации, моменты, cтандартизованные моменты. Пример визуализаций описательных статистик. Исследование частей выборки (фолдов), визуализация важностей признаков, первичные действия при анализе признака. Визуализация отдельных признаков: диаграммы, гистограммы, плотности распределения, выбор числа бинов, трансформации признаков. Визуализация категориальных признаков: гистограммы, диаграммы-пироги и области, уточнение природы признака.|
| [**Искусство визуализации (часть 3 - многомерный анализ)**](./2020/PZAD2020_023vismultivar_03.pdf) 02.10.2020 | Визуализация пары признаков: корреляция, зависимость признаков, независимость признаков, типичные значения, выбросы, кластеры. Диаграмма рассеивания. Использования шума для визуализации. Сводные таблицы, треугольные зависимости. Визуализации пары «вещественный признак» – «категориальный». Сравнение с бенчмарком. Визуализация «ответ алгоритма» – «ответ алгоритма». Визуализация «ответ алгоритма» – «признак». Деформации ответов и признаков. Residual plot. Корреляции. 3D-визуализации. Визуализация служебных признаков. Проверка соответствия «train-test». Агрегация.|
| [**Метрики качества. Часть 1. Функции ошибки в задаче регрессии**](./2020/PZAD2020_031err_regression_10n.pdf) 09.10.2020 | Средний модуль отклонения MAE(MAD), средний квадрат отклонения MSE, его производные: RMSE, коэффициент детерминации R2, вероятностное и невероятностное обоснование RMSE, функция Хьюбера, Logcosh, обобщения MAE и RMSE, процентные функции ошибок (SMAPE, MAPE, PMAD), ошибки, основанные на сравнении с бенчмарком (MRAE, REL_MAE, PB), нормированные ошибки (MASE), несимметричные ошибки, ошибки с точностью до порога, использование функций ошибок для генерации признаков.|
| [**Метрики качества. Часть 2. Чёткая бинарная классификации**](./2020/PZAD2020_032err_classification_20n.pdf) 09.10.2020 | Матрица ошибок / несоответствий «Сonfusion Matrix», точность (Accuracy, MCE), ошибки 1 и 2 рода, полнота (Recall, TPR, Sensitivity), специфичность (Specificity , TNR), точность (Precision),обратная точность (Inverse Precision), FPR(False Positive Rate), F1-мера, F-мера, Каппа Коэна (Cohen's Kappa), , Коэффициент Мэттьюса (MCC), Сбалансированная точность (Balanced Accuracy), сравнение функционалов на модельной задаче.|
| [**Метрики качества.  Часть 3: скоринговые функции и кривые в машинном обучении**](./2020/PZAD2020_033err_scoreandcurves_13n.pdf) 23.10.2020 | Задачи с ответом в виде оценки принадлежности, скоринговые ошибки: логистическая функция ошибки Log Loss, MSE, Misclassification Loss, Exploss; Площадь под ROC-кривой, AUROC, GINI (кривая Лоренца), кривая «полнота-точность», Gain Curve (Chart), Lift Curve (Chart), Kolomogorov Smirnov chart, The Gains Table.|
| [**Метрики качества. Часть 4: многоклассовые задачи, ранжирование, кластеризация**](./2020/PZAD2020_034err_multirankcluster_03.pdf) 23.10.2020 | Weighted kappa, Многоклассовая задача «Multi-label»: Hamming Loss, Log Loss (cross-entropy), Mean Probability Rate, MSE, MAE, многоклассовый AUCROC, точность, полнота, F1-мера, сбалансированная точность «Balanced accuracy». Усреднения: микро-подход, макро-подход, макро-подход с весами, по объектам. *Оценка результатов поиска/рекомендаций: Precision at n, Average Precision at n, Mean Average Precision, Concordant – Discordant ratio, Mean Reciprocal Rank (MRR), Cumulative Gain at n, Discounted Cumulative Gain at n, Normalized DCG, Ранговые корреляции, Expected reciprocal rank (ERR). Редакторское расстояние.* Задача с «неклассическим целевым вектором»: Коэффициент Жаккара (Jaccard), коэффициент Шимкевича-Симпсона (Szymkiewicz, Simpson), коэффициент Браун-Бланке (Braun-Blanquet), коэффициент Сёренсена (Sörensen), коэффициент Кульчинского (Kulczinsky), коэффициент Отиаи (Ochiai). *Оценка результатов кластеризации: внешняя оценка (External evaluation): взаимная информация (mutual information - MI), скорректированная взаимная информация (Adjusted mutual information), V-мера, Adjusted Rand index, общий подход (Rand index, Fowlkes-Mallows index - FMI). Внутренняя оценка (Internal evaluation): Davies–Bouldin index, Dunn index, Silhouette, Calinski-Harabasz Index (Variance Ratio Criterion).*

курсивом - пропущенное|
| [**Метрики качества: задачи и кейсы**](./2020/PZAD2020_035minfunc_05nold.pdf) 30.10.2020 | Как настраиваться на конкретные функции. Идеология РП. Критерий расщепления для AUC. CASE: Вычисление матожидания ошибки. Задачи с интервальными признаками. Обоснование деформации логарифмом. Градиентный спуск. Задачи для решения.|





### домашние задания
| срок | задание |
| :-- | :-- |
| 08.10.2020 | **Подготовить pdf-презентацию для игры "Что за данные"?** Найти 2 визуализации и представить их на pdf-презентации в виде вопроса-ответа (как было на лекции). Организуйте презентацию так, чтобы её можно было листать и играть в игру постороннему человеку.  Презентация заливается в classroom (к этому заданию) в формате pdf, название файла *z1_ИвановИИ.pdf*|
| 08.10.2020 | **Сделать визуализацию данных реальной задачи.** Выбрать датасет, отметить его в таблице (в классруме), лучше выбирать со вкладки Datasets сайта kaggle.com из свежих данных (< 1 года). Крайне желательно небольшое количество кёрнелов - если Ваши визуализации будут дублировать уже существующие, задание не будет засчитано. Старайтесь выполнить установку "я первый обнаружил, что ...". Любой другой датасет (старый / с другого сайта), надо согласовать с лектором в телеграме. Визуализация иммитирует полноценный EDA - поиск закономерностей и нелогичностей в данных, ыдвижение гипотез и т.п. (см. лекцию).  В classroom (к этому заданию) загружаются 2 файла: *z2_ИвановИИ.pdf* - презентация, *z2_ИвановИИ.ipynb* - код (м.б. в архиве zip).|
| 23.10.2020 | **MoA Prediction - первая посылка** Начать решать соревнование https://www.kaggle.com/c/lish-moa/ Необходимо изучить задачу и сделать посылку решения - открытый ноутбук. Лучше сделать также EDA по задаче. Команду называйте в виде Ivanov Ivan (PZAD).|
| 30.10.2020 | **MoA Prediction - подготовка к мозговому штурму** Продолжаем решать соревнование https://www.kaggle.com/c/lish-moa/ Загрузить в классрум презентацию с находками по задаче.|
