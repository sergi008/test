import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_excel('data.xlsx')
print("Первые 5 записей:")
print(df.head())

plt.bar(df['Категория'], df['Значение'])
plt.title('Столбчатая диаграмма значений по категориям')
plt.xlabel('Категория')










