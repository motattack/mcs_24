# mcs_24 [Расписание](https://docs.google.com/spreadsheets/d/1SUWGYB0hIYg-Anky_vYbtH3Vla9_gs85lXaNUBEqVTE/edit?usp=sharing)

## Мат стат [Пособие](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/ms_nsu07.pdf) | [Пособие Теорвер](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/portr.pdf) | [Практика 1](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/Praktika_1_nov.pdf) -> [jupyter](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/lesson1_new.ipynb) | [Практика 2](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/Praktika_2.pdf)

## Мат физика [Пособие](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/AlekseevMono2011.pdf) | [Новые главы](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/emp17-13New_gl_1.pdf) | [Экзамен](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/MathPhys_Questions01_2023.pdf) | [Устный экзамен](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/MathPhys_Questions02_2023.pdf)

## Функан [Введение](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/vvedenie_v_predmet.pdf) | [Пособие 1](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/Lektsii_Po_Fa-1.pdf) | [Пособие 2](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/Lektsii_Po_Fa-2.pdf) | [Идз](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/Zadachi_Dlya_Idz-Funkan.pdf)

## Числаки [Функции](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/Lab_1-2_Zadanie_Dlya_1_Lab.pdf) | [Лаба №1](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/Lab_1_2_zadacha_koshi_i_kraevaya_zadacha.pdf)

## Экономика [Выбор страны](https://docs.google.com/spreadsheets/d/1r7hIE2U4t7hJR_7NQNpGQFKQd7QYfGfXZuOuwOTgFWQ/edit?usp=sharing)

## Мат моделирование (...---...) [пиздец]
  ### Лаба №1
  Необходимо построить модель нагрева нагревателя утюга в трех вариантах (без терморегулятора/с терморегулятором/с умным терморегулятором)
  ```math
    \frac{dT}{dt} = \frac{\rho - kS\left(T - T_{0}\right) - \sigma S\left(T^{4} - T_{0}^{4}\right)}{mc}
    - \textit{Решать можно методом Эйлера},
  ```
  где $S$ - площадь, $\rho$ - мощность, $\sigma$ - постоянная Стефана-Больцмана.
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

  ### Лаба №2
  Модель конкуренции/соперничества (хищник-жертва).
  N(t) - масса жертвы
  M(t) - масса хищника

  N и M вступают во взаимодействие
  ```math
  \frac{dN}{dt} = aN
  ```

  ```math
  \frac{dM}{dt} = -bM
  ```
  где $a, b > 0$

  Скорость роста $a \rightarrow (a - cM)$
  при взаимодействии $-b \rightarrow (-b + dN)$

  Мат модель
  ```math
  \begin{equation}
      \begin{cases}
        \frac{dN}{dt} = (a - cM)N \\
        \frac{dM}{dt} = (-b + dN) M \\
        N\left(0\right) = N_{0} \\
        M\left(0\right) = M_{0}
      \end{cases}
  \end{equation}
  ```

  Анализ мат модели.
  Есть стационарные точки $\left(=0\right)$ ?
  1. $` N_{0} = \frac{b}{d}, \quad M_{0} = \frac{a}{c} `$
  2. $`\frac{dN}{dM} = \frac{\left(a - cM\right)N}{\left(-b + aN\right)M} \Rightarrow`$

  $b\ln(N) - dN + a\ln(M) - cM = const$

  Вычислительная схема (псевдо маткад)
  
  $$Origin := 1$$
  
  ```math
  F\left(t, x\right) =
  \begin{vmatrix}
  \left(a - bx_{2}\right)x_{1}\\
  \left(-b + dx_{1}\right)x_{2}
  \end{vmatrix}
  ```

  ```math
  X := rkfixed(x0, 0, 10, 200, F)
  ```

  ```math
  t := X^{<1>}
  ```

  ```math
  N := X^{<2>}
  ```

  ```math
  M := X^{<3>}
  ```

  X - матрица.
  Нужно вывести таблицу со столбцами (время, x1, x2).

  Далее нужен рисунок как N и M взаимодействуют 
  ![Шиза 1](https://raw.githubusercontent.com/motattack/mcs_24/main/mcm/shiza1.png)
  
  Так же под рисунком должно быть описание (например: Рис 1. Полная шизофрения)

  Затем нужен фазовый портрет.
  
  ![Шиза 2](https://raw.githubusercontent.com/motattack/mcs_24/main/mcm/shiza2.png)

  Нужно указать какие коэффициенты брали для мат модели в целом.

  Для численных экспериментов значения брать примерно такие значения.
  $$a \widetilde{=} 2 \div 4; \quad b = \widetilde{=} 1 \div 4$$
  $$c \widetilde{=} 1 \div 3; \quad d = \widetilde{=} 1 \div 3$$
  $$N \widetilde{=} 2 \div 4; \quad M = \widetilde{=} 1 \div 4$$

  ### Лаба №3
  Мат модель математического Маятника
  1. Малые колебания
  2. Большие колебания
  3. С трением
  4. С появлением силы $f$, которая подталкивает маятник

  Не шизите с материальной точной (кто-то сказал пермякову, что это жидкость)
  
  Маятник можно задавать координатами $(x, y)$ или через момент $\alpha$. Делаете как больше нравится

  Если через координаты то будет два уравнения движения Ньютона
  ```math
  \begin{equation}
      \begin{cases}
       m\ddot{x} = F_{x}\\
       m\ddot{y} = F_{y}
      \end{cases}
  \end{equation}
  ```

 Если через $\alpha$, то будет уравнение баланса

 $I \cdot \frac{d^2\alpha}{dt^2} = M$ - момент сил.

 $I = m \cdot L^2$ - момент инерции

 $M = mg\sin\left(\alpha\right) * L$ - момент силы

 $mL^2 \frac{d^2\alpha}{dt^2} + mgL\sin\left(\alpha\right) = 0$ | $: mL^2$

 $\frac{d^2\alpha}{dt^2} + \left(\frac{g}{L}\right)\sin\left(\alpha\right) = 0$

 Пусть $\omega = \frac{g}{L}$

   ```math
  \begin{equation}
      \begin{cases}
      \frac{d^2\alpha}{dt^2} + \omega^2 \sin\left(\alpha\right) = 0\\
      \alpha\left(0\right) = \alpha_{0}\\
      \alpha'\left(0\right) = \alpha_{1}
      \end{cases}
  \end{equation}
  ```
Уравнения малых колебаний. При малых углах $\sin\left(\alpha\right) = \alpha$

$\frac{d^2\alpha}{dt^2} + \omega^2 \alpha = 0$

Вар 1. Малые колебания $\alpha_{0} \approx 5 \degree$

Вар 2. Большие колебания $\alpha_{0} \approx 90 \degree$

На графике показать, что период изменяется. 1 и 2 будут ровные. 3 будет сильно меняться.

Нелинейные колебания
```math
  \begin{equation}
      \begin{cases}
      \omega = \omega\left(x\right)\\
      \ddot{x} + \omega^2 x = 0
      \end{cases}
  \end{equation}
```

3. Появляется коэф трения $k$. $kx$ - затухание.
4. Внешние силы (периодические). Показать эффект резонанса.

Построить амплитуду колебаний.

По словам пермякова такая работа занимает $\approx 8$ страниц

