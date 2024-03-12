# mcs_24_2 [Расписание](https://docs.google.com/spreadsheets/d/1SUWGYB0hIYg-Anky_vYbtH3Vla9_gs85lXaNUBEqVTE/edit?usp=sharing)

## Мат стат [Пособие](https://raw.githubusercontent.com/motattack/mcs_24_2/main/stat/ms_nsu07.pdf) | [Пособие Теорвер](https://raw.githubusercontent.com/motattack/mcs_24_2/main/stat/portr.pdf) | [Практика 1](https://raw.githubusercontent.com/motattack/mcs_24_2/main/stat/Praktika_1_nov.pdf) -> [jupyter](https://raw.githubusercontent.com/motattack/mcs_24_2/main/stat/lesson1_new.ipynb) | [Практика 2](https://raw.githubusercontent.com/motattack/mcs_24_2/main/stat/Praktika_2.pdf)

## Мат физика [Пособие](https://raw.githubusercontent.com/motattack/mcs_24_2/main/mmm/AlekseevMono2011.pdf) | [Новые главы](https://raw.githubusercontent.com/motattack/mcs_24_2/main/mmm/emp17-13New_gl_1.pdf) | [Экзамен](https://raw.githubusercontent.com/motattack/mcs_24_2/main/mmm/MathPhys_Questions01_2023.pdf) | [Устный экзамен](https://raw.githubusercontent.com/motattack/mcs_24_2/main/mmm/MathPhys_Questions02_2023.pdf)

## Функан [Введение](https://raw.githubusercontent.com/motattack/mcs_24_2/main/funcan/vvedenie_v_predmet.pdf) | [Пособие 1](https://raw.githubusercontent.com/motattack/mcs_24_2/main/funcan/Lektsii_Po_Fa-1.pdf) | [Пособие 2](https://raw.githubusercontent.com/motattack/mcs_24_2/main/funcan/Lektsii_Po_Fa-2.pdf) | [Идз](https://raw.githubusercontent.com/motattack/mcs_24_2/main/funcan/Zadachi_Dlya_Idz-Funkan.pdf)

## Числаки [Функции](https://raw.githubusercontent.com/motattack/mcs_24_2/main/num_meth_of_dif_eq/Lab_1-2_Zadanie_Dlya_1_Lab.pdf) | [Лаба №1](https://raw.githubusercontent.com/motattack/mcs_24_2/main/num_meth_of_dif_eq/Lab_1_2_zadacha_koshi_i_kraevaya_zadacha.pdf)

## Мат моделирование (...---...)
  ### Лаба №1
  Необходимо построить модель нагрева нагревателя утюга в двух вариантах (без терморегулятора/с терморегулятором)
  ```math
    \frac{dT}{dt} = \frac{P - kS\left(T - T_{0}\right) - \sigma S\left(T^{4} - T_{0}^{4}\right)}{mc}
    - \textit{Решать можно методом Эйлера},
  ```
  где $S$ - площадь, $P$ - мощность, $\sigma$ - постоянная Стефана-Больцмана.
  $T_{0} = T_{a}$ - начальное (= атмосферной температуре)
  $T, T_{0}$ - в кельвинах.
  
  Что должно быть обязательно:
  1. Введение
  2. Соотношения, формулы, законы, правила, подходы, методы
  3. Математическая задача (модель) - уравнение или система + краевые условия
  4. Анализ (существует ли вообще !решение)
  5. Вычислительный алгоритм для решения (если есть, то аналитическое решение)
  6. Программа
  7. Тестирование (численные эксперименты[примеры])
  8. Визуализация к тестам
  9. Заключение
