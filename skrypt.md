%Egzamin wstępny

# Mechanika

## Własności pary sił
Para sił to układ dwóch sił przyłożonych do danego ciała, równych sobie co do wartości i przeciwnie skierowanych, ale zaczepionych w różnych punktach ciała. Siła wypadkowa jest równa zeru.
Moment pary sił równy jest iloczynowi wartości siły i odległości pomiędzy ich liniami działania
$$\tau = \frac{P}{s}$$

* Działanie pary sił na ciało sztywne nie ulegnie zmianie, gdy parę przesuniemy w dowolne położenie w jej płaszczyźnie działania.
* Działanie pary sił na ciało sztywne nie ulegnie zmianie, gdy zmienimy siły pary i jej ramię tak, aby wektor momentu pary został niezmieniony.
* Działanie pary sił na ciało sztywne nie ulegnie zmianie, gdy parę sił przesuniemy na płaszczyznę równoległą do jej płaszczyzny działania.
* Działanie pary sił na ciało sztywne nie ulegnie zmianie, jeżeli moment pary się nie zmieni.

## Przypadki redukcji przestrzennego układu sił
Dowolny układ sił można zredukować do **wektora głównego** i **momentu głównego**
Wartość wektora głównego jest dana jako
$$\vec{W_g}=\sum_i\vec{P_i}$$
Wartość momentu głównego jest dana jako
$$\vec{M_g}=\sum_i\vec{M_i}$$
Przypadki szczególne:

1. $\vec{W_g}\neq0,\quad\vec{M_g}\neq0,\quad\vec{W_g}\parallel\vec{M_g}$ - układ redukuje się do **skrętnika**,
2. $\vec{W_g}\neq0,\quad\vec{M_g}\neq0,\quad\vec{W_g}\perp\vec{M_g}$ - układ redukuje się do **siły odsuniętej od bieguna**,
3. $\vec{W_g}\neq0,\quad\vec{M_g}=0$ - układ redukuje się do **siły**,
4. $\vec{W_g}=0,\quad\vec{M_g}\neq0$ - układ redukuje się do **pary sił**,
5. $\vec{W_g}\neq0,\quad\vec{M_g}\neq0,\quad\vec{W_g}\not\parallel\vec{M_g},\quad\vec{W_g}\not\perp\vec{M_g}$ - układ redukuje się do **skrętnika o osi odsuniętej od bieguna**.

## Warunki równowagi dowolnego układu sił
$$\vec{W_g}=\sum_i\vec{P_i}=0\quad\land\quad\vec{M_g}=\sum_i\vec{M_i}=0$$

## Chwilowy środek obrotu i przyspieszenia
W ruchu płaskim istnieje punkt, którego **prędkość jest równa zero**. Jest to chwilowy środek obrotu.
Z każdego położenia w inne położenie daje się przesunąć przez obrót dokoła punktu leżącego w tej płaszczyźnie, zwanego środkiem obrotu skończonego. W przypadku szczególnym, dla położeń w czasie $t$, oraz $t+dt$, gdzie $dt\to0$, środek obrotu skończonego nazywa się chwilowym środkiem obrotu.
Dla translacji chwilowy środek obrotu leży w nieskończoności. W przypadku toczenia bez poślizgu chwilowy środek obrotu jest w punkcie styku.

W ruchu płaskim istnieje punkt, którego **przyspieszenie równa się zero**. Jest to chwilowy środek przyspieszenia.

## Prędkość i przyspieszenie punktu w ruchu złożonym

* Prędkość punktu względem nieruchomego układu współrzędnych $O_{xyz}$ nazywamy **prędkością bezwzględną** $v_b$.
* Prędkość punktu względem ruchomego układu współrzędnych $O_{\xi\eta\zeta}$ nazywamy **prędkością względną** $v_w$.
* Prędkość układu ruchomego $O_{\xi\eta\zeta}$ względem układu nieruchomego $O_{xyz}$ nazywamy **prędkością unoszenia** $v_u$.

Prędkość **bezwzględna** jest sumą prędkości **względnej** i prędkości **unoszenia**.
$$\vec{v_b}=\vec{v_w}+\vec{v_u}$$

Przyspieszenie **bezwzględne** jest sumą przyspieszenia **względnego**, przyspieszenia **unoszenia** i przyspieszenia **Coriolisa**.
$$\vec{a_b}=\vec{a_w}+\vec{a_u}+\vec{a_c}$$

Przyśpieszenie **Coriolisa** jest podwojonym iloczynem wektorowym prędkości kątowej i prędkości względnej.
$$\vec{a_c}=2\vec{\omega}\times\vec{v_w}$$
$$\vec{a}\times\vec{b}=||\vec{a}||\cdot||\vec{b}||\cdot\sin\theta\cdot\vec{n}$$

## Zasady dynamiki stosowane w dynamice układów punktów materialnych

* Zasady dynamiki Newtona
  1. W inercjalnym układzie odniesienia, jeśli na ciało nie działa żadna siła lub siły działające równoważą się, to ciało pozostaje w spoczynku lub porusza się ruchem jednostajnym prostoliniowym.
  2. W inercjalnym układzie odniesienia jeśli siły działające na ciało nie równoważą się (czyli wypadkowa sił $\vec {F}_{w}$ jest różna od zera), to ciało porusza się z przyspieszeniem wprost proporcjonalnym do siły wypadkowej, a odwrotnie proporcjonalnym do masy ciała.
  3. Oddziaływania ciał są zawsze wzajemne. W inercjalnym układzie odniesienia siły wzajemnego oddziaływania dwóch ciał mają takie same wartości, taki sam kierunek, przeciwne zwroty i różne punkty przyłożenia (każda działa na inne ciało).
* Zasada zachowania pędu
$$\sum_i \vec{p_i} = idem,\quad \frac{d\vec{p}}{dt}=0$$
* Zasada zachowania krętu
$$\sum_i\vec{L_i}=idem,\quad\frac{d\vec{L}}{dt}=0$$
* Zasada zachowania energii mechanicznej
$$E_k+E_p = idem$$
* Zasada równości energii kinetycznej i pracy
$$\Delta E_k = W$$
* Zasada d'Alemberta
$$\delta W = 0 $$
* Zasada Lagrange'a
$$\underset{zg.\,z\,w.}{\forall \delta x_i}\quad\delta W = \sum_iX_i\delta x_i = 0$$

## Dynamiczne równania bryły w ruchu postępowym, obrotowym, płaskim i kulistym
TODO

## Energia kinetyczna bryły w ruchu postępowym, obrotowym, płaskim i kulistym
TODO

## Równania Lagrange'a I i II rodzaju
TODO

# Wytrzymałości materiałów

## Krzywe statycznego rozciągania, charakterystyczne parametry materiałowe
Przykładowa rzeczywista:

![](./media/przykladowyrozciagania.pdf)
Model sztywno-plastyczny:

![](./media/sztywnoplastyczny.pdf)
Model sprężysto-plastyczny:

![](./media/sprezystoplastyczny.pdf)
Model sztywno-plastyczny z umocnieniem:

![](./media/sztywnoplastycznyumocnienie.pdf)
Model sprężysto-plastyczny z umocnieniem:

![](./media/sprezystoplastycznyumocnienie.pdf)

Stałe materiałowe:
* Moduł Young'a - odkształcenie od naprężeń
* Moduł plastyczności - odkształcenie od naprężeń przy uplastycznieniu
* Liczba Poisson'a - stosunek odkształcenia poprzecznego do odkształcenia podłużnego przy osiowym stanie naprężenia
* Moduł Kirchoff'a - odkształcenie postaciowe od naprężeń
* Granica sprężystości
  * Wyraźna
  * Umowna (0.05%)
* Granica plastyczności
  * Górna
  * Dolna
  * Umowna (0.2%)
* Wytrzymałość doraźna

## Czyste zginanie
Naprężenia w odległości h od osi obojętnej
$$\sigma(h) = \frac{M_g}{I}*h$$
Naprężenia maksymalne
$$\sigma_{max} = \frac{M_g}{W_g}$$
Różniczkowe równanie linii ugięcia
$$EI\frac{d^2y}{dz^2} = -M_g(z)$$
Różniczkowe równanie kątu obrotu
$$EI\frac{dy}{dz}= \int -M_g(z)dz+C$$
Równanie linii ugięcia
$$EIy = \int\int -M_g(z)dzdz +Cz +D$$
C, D - stałe całkowania z warunków brzegowych

## Skręcanie przekrojów kołowo-symetrycznych
Naprężenia na promieniu r od osi głównej centralnej (Dla koła $I=\frac{\pi d^4}{32}$)
$$\tau =\frac{M_s}{I_0}r$$
Naprężenia maksymalne
$$\tau_{max} = \frac{M_sD}{2I_0}$$

Kąt skręcenia
$$\alpha=\frac{M_sl}{GI}\quad \lor \alpha = \int_0^l\frac{M_s(x)}{GI}dx$$

## Wytężenie materiału
Hipotezy wytężeniowe - założenie dotyczące tego, jaka wielkość fizyczna związana ze stanem naprężenia i odkształcenia, decyduje o wytężeniu materiału
* Galileusz: $\sigma_{red}=\sigma_1$, decyduje $\sigma_{max}$,
* de Saint Venant: $\sigma_{red}=\sigma_1-\nu(\sigma_2+\sigma_3)$, decyduje max. $\varepsilon_{osiowe}$,
* Tresci-Guest: $\sigma_{red}=\sigma_1-\sigma_3$, decyduje $\tau_{max}$
* Huber-Mises-Hencky: $\sigma_{red}=\frac{1}{\sqrt{2}}\sqrt{(\sigma_1-\sigma_2)^2+(\sigma_2-\sigma_3)^2+(\sigma_1-\sigma_3)^2}$, decyduje energia właściwa odkształcenia postaciowego.

Naprężenie zredukowane - taka wartość naprężenia, wyznaczona dla danego stanu naprężenia przy użyciu wybranej hipotezy, która przy jednoosiowym rozciąganiu, wywołałaby identyczne wytężenie.
