# mcs_24 [Расписание](https://docs.google.com/spreadsheets/d/1SUWGYB0hIYg-Anky_vYbtH3Vla9_gs85lXaNUBEqVTE/edit?usp=sharing)

## Числаки [Марчук](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/vychmat.pdf) | [Марчук 2](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/rashep.pdf) | [Завьялов](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/splain.pdf) | [Срочко](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/Ch_method.pdf)
Вариационные и проекционные методы математической физики.
1.	Формулировка задачи вариационного исчисления, вывод уравнения Эйлера.
2.	Первая краевая задача.
3.	Вторая краевые задача.
4.	Теорема об эквивалентности решения краевой задачи нахождению экстремума функционала. Доказательство необходимости.
5.	Теорема об эквивалентности решения краевой задачи нахождению экстремума функционала. Доказательство достаточности.
6.	Одномерное пространство Соболева, норма в этом пространстве.
7.	Двумерное пространство Соболева, норма в этом пространстве.
8.	Метод Ритца.
9.	Метод Галеркина.
10.	Свойства конечных элементов в МКЭ.
11.	Базис из функций с минимальными носителями в одномерном пространстве.
    
Литература для подготовки.
1.	Учебное пособие Марчук Г.И. Методы вычислительной математики. М.: Наука, 1980, пункт 2.2 «Вариационные методы в математической физике»,
2.	Учебное пособие Завьялов Ю.С., Квасов Б.И., Мирошниченко В.Л. Методы сплайн-функций. – М.: Наука, 1980 г., глава 11 «Метод конечных элементов», параграф 1 «Понятие о методе конечных элементов».


## Мат стат [Пособие](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/ms_nsu07.pdf) | [Пособие Теорвер](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/portr.pdf) | [Практика 1](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/Praktika_1_nov.pdf) -> [jupyter](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/lesson1_new.ipynb) | [Практика 2](https://raw.githubusercontent.com/motattack/mcs_24/main/stat/Praktika_2.pdf)

## Мат физика [Пособие](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/AlekseevMono2011.pdf) | [Новые главы](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/emp17-13New_gl_1.pdf) | [Экзамен](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/MathPhys_Questions01_2023.pdf) | [Устный экзамен](https://raw.githubusercontent.com/motattack/mcs_24/main/mmm/MathPhys_Questions02_2023.pdf)

## Функан [Введение](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/vvedenie_v_predmet.pdf) | [Пособие 1](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/Lektsii_Po_Fa-1.pdf) | [Пособие 2](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/Lektsii_Po_Fa-2.pdf) | [Идз](https://raw.githubusercontent.com/motattack/mcs_24/main/funcan/Zadachi_Dlya_Idz-Funkan.pdf)

## Числаки П [Функции](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/Lab_1-2_Zadanie_Dlya_1_Lab.pdf) | [Лаба №1](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/Lab_1_2_zadacha_koshi_i_kraevaya_zadacha.pdf) | [Задание 2](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/zadanie_2.pdf) < [И1](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/tabfix_1.jpg) < [И2](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/tabfix_2.jpg) < [И3](https://raw.githubusercontent.com/motattack/mcs_24/main/num_meth_of_dif_eq/tabfix_3.jpg)

## Экономика [Выбор страны](https://docs.google.com/spreadsheets/d/1r7hIE2U4t7hJR_7NQNpGQFKQd7QYfGfXZuOuwOTgFWQ/edit?usp=sharing)

## Мат моделирование (...---...)
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

 Пусть $\omega^2 = \frac{g}{L}$

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

### Лаба №4
  Движение материальной точки во вращающейся системе координат

  $\omega = \frac{2\pi}{T} = \frac{2\pi}{24\cdot 60\cdot 60}$

  Уравнение движения $F=ma$.
  
  $m\frac{dV}{dt} = F$

  Сила Кориоли́са $F_{k} = 2\left[w \times v\right]m$ - перпендикулярно скорости.
  
  Подставляем
  
  $m\frac{dV}{dt} = 2\left[w \times v\right]m$
  
  $\frac{dV}{dt} = 2\left[w \times v\right]$

  Траектория это $x = x\left(t\right)$ и $y = \left(t\right)$.
  
  $U = U\left(t\right)$ и $V = V\left(t\right)$
  
  $\Rightarrow$ $U = \frac{dx}{dt}$, $V = \frac{dy}{dt}$
  
  Системка
  ```math
  \begin{equation}
      \begin{cases}
       \frac{dU}{dt} = 2 \omega V,\\
       \frac{dV}{dt} = -2 \omega U,\\
       \frac{dx}{dt} = U,\\
       \frac{dy}{dt} = V,\\
       U\left(0\right) = U0,\\
       V\left(0\right) = V0,\\
       x\left(0\right) = x0,\\
       y\left(0\right) = y0,
      \end{cases}
  \end{equation}
  ```

  При анализе. Сила кориолиса перпендикулярна (скалярное даст 0) - не производит работу.
  
  Можно показать
  
  $u\frac{dU}{dt} = 2\omega VU$
  
  $V\frac{dV}{dt} = -2\omega UV$

  (сложили то, что выше)
  
  $U\frac{dU}{dt} + V\frac{dV}{dt} = 0$
  
  $\frac{1}{2} \left(\frac{dU^2}{dt} + \frac{dV^2}{dt}\right) = 0$
  
  $\frac{d}{dt} \left(\frac{U^2}{2} + \frac{V^2}{2}\right) = 0$ - изменение кинетической энергии = 0.

  Можно анализ траектории -- показать, что будет окружность и какого радиуса. Кинетическая в потенциальную.
  $\left|\bar{V}\right| \approx 1 \div 10$ м/с
  
  Нужно показать при разных скоростях (2-3 варианта) - из 1 точки.
  
  Выводить примерно такую таблицу
  | $t_i$ | $U_i$ | $V_i$ | $x_i$ | $y_i$ | $V_i^2 + U_i^2$ | $k = \frac{k_i - k0}{k0}$ |
  |-------|-------|-------|-------|-------|-----------------|---------------------------|
  | | | | | | | |

  Построить график (по абсциссе $t$, по ординате $k$) - будет просто прямая.

  Модификаиция. Теперь стоим в точке - есть турбулентность.
  
  Скорость теперь:
  $V = \bar{V} + V_{t}$, где V с волной это средняя скорость, а с t - турбулентности.
  
  Предлагается $`U + U'_{t}`$ и $`V + V'_{t}`$
  
  $i=1,2$. $r_{i}$ - случайное число $\approx 0.1$.
  
  $U \Rightarrow U + r_{1}\left|U\right|$
  
  $V \Rightarrow V + r_{2}\left|U\right|$
  
  Будет график, где круги смещены, но в "целом можно их поймать в один круг".
  
  (ШИЗТУНГ: Он хочет круги, а не элипсы, следите графиком. Он не скушает y = {0, 1, 2, 3, ..., 15} x = {$`10^2`$, $`10^3`$, $`10^4`$, ..., $`10^{15}`$}.
  Не пишите, что элипс шарообразуется или элипс принимает форму шара).
