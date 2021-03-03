{% include libs/mathjax.html %}
# [База знаний](/../../../readme.md)
# [Технологии ИИ и машинной графики](lesson_00.md)
### [Занятие 1. (2021-02-11)](lesson_01.md)
## <center> Занятие 2. (2021-02-18) </center>

### <center> Пройденные тетради </center>

1. [Notebook - Intro.ipynb](https://github.com/Aynur19/AI-in-Study/blob/master/ML%20%26%20CV/NeuroWorkshop-master/Notebooks/Intro.ipynb)


### <center> Введение в нейронные сети </center>
**`Два взгляда на нейронные сети`**:
1. Восходящий подход к искусственному интеллекту
2. Способ усложнения и комбинирования базовых алгоритмов машинного обучения
    - обучение с учителем (**`supervised learning`**)
    - обучение без учителя (**`unsupervised learning`**)

### <center> Обучение с учителем </center>
**Дано:**
1. Обучающая выборка $$\mathbf{X} \in \mathbb{R}^{n \times k}$$
    - $$n$$ - размер выборки
    - $$x_i$$ представлено вектором свойств размерности $$k$$
2. Известные значения целевой функции $$\mathbf{Y}$$ 
($$y_i$$ соответствует вектору свойств $$x_i$$
)
    - $$\mathbf{Y} \in \mathbb{R}^{n \times 1}$$ (задачи регрессии)

    - $$\mathbf{Y} \in C^{n \times 1}$$, где $$y_i \in C$$ (задачи классификации на $|C|$ классов)


### <center> Самостоятельная работа </center>
1. Подготовить окружение для работы на Jupyter Notebook

