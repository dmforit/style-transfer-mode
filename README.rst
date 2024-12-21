|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: style transfer
    :Тип научной работы: M1P
    :Автор: Каратыщев Дмитрий Иванович
    :Научный руководитель: к.ф.-м.н., Китов Виктор Владимирович

Abstract
========

Перенос стиля изображений синтезирует новые изображения, сохраняя содержание исходного изображения и перенимая стиль референсного изображения. Недавние достижения, такие как метод Restorable Arbitrary Style Transfer (RAST), представляют архитектуры, обеспечивающие гибкость и обратимость манипуляций со стилем. В данном исследовании пересматривается архитектура RAST, реализуется ее структура и проводится серия экспериментов для оценки и улучшения производительности. Вклад включает исследование методом исключения для оценки значимости различных компонентов функции потерь, введение функции потерь на идемпотентность для обеспечения согласованности переноса стиля, использование многоэтапной функции потерь, адаптированной для изображений низкого разрешения, и интеграцию функции LPIPS (Learned Perceptual Image Patch Similarity) для повышения перцептивного качества. Также исследуются упрощения архитектуры путем изоляции отдельных компонентов оригинальной модели. Эксперименты демонстрируют сильные и слабые стороны модификаций, предоставляя идеи для улучшения методов произвольного переноса стиля.

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
