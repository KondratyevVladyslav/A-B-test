 A/B Test — Subscription Conversion

Pet Project | Junior Data Analyst

  Про проєкт
Аналіз A/B тесту для перевірки впливу повідомлення про **знижку 50%** на конверсію користувачів у підписку.
  Мета
Збільшити конверсію в платну підписку.
 Гіпотеза
Користувачі, які бачать знижку, частіше оформлюють підписку.
 Дані
- Користувачів: **19 998**
- Період: **03.07.2023 – 25.07.2023**
- Метрика: `conversion`

| Група | Конверсія |
|------|-----------|
| A | 6.1% |
| B | 8.9% |

 Аналіз
- Використано **t-test (one-sided)**
- **p-value < 0.001**
- Різниця статистично значуща

 Висновок
Варіант **B (зі знижкою)** показав вищу конверсію та рекомендований до впровадження.

  Стек
`Python` · `Pandas` · `NumPy` · `SciPy` · `Matplotlib` · `Seaborn`
 Запуск
```bash
pip install -r requirements.txt
```
```bash
notebooks/AB_test.ipynb
```
 Автор
Kondratyev Vladyslav/Junior Data Analyst  
Open to opportunities 
