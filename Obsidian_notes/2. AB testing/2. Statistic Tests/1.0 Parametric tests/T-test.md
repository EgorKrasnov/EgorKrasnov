t-статистика строится обычно по следующему общему принципу: в числителе — случайная величина с нулевым математическим ожиданием (при выполнении нулевой гипотезы), а в знаменателе — выборочное стандартное отклонение этой случайной величины, получаемое как квадратный корень из несмещённой оценки дисперсии.

If you want to use T-test then data should satisfy this requirements
1. independence of each observation
	- [[Chi-Squared test]]
2. Homogeneity of Variance (optional)
	-  [[Levene's test]] if test failed then use [[Welch’s t-test]]
3. Normal distribution 
	- [[Shapiro–Wilk test]] or [[Kolmogorow-Smirnow test]]
	- QQ plot
4.  Sample size > 30 

>Одно из допущений, лежащих в основе t-критерия для независимых выборок, состоит в приблизительном равенстве дисперсий генеральных совокупностей, из которых взяты выборки; Если это условие не выполняется и дисперсии генеральных совокупностей в реальности различаются, возрастает риск ошибок как первого, так и второго рода.
  Задача проверки гипотезы о двух независимых выборках с различающейся дисперсией известна под названием проблемы Беренса–Фишера (Behrens–Fisher), и было предложено несколько ее решений.
  Примеры такого рода тестов включают тест Левене, тест Брауна–Форсайта и тест Бартлетта
  
![[Pasted image 20240529184923.png]]
