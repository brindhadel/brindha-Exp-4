# brindha-Exp-4
from pandas import read_csv
from matplotlib import pyplot
series=read_csv(""C:\Users\Brindha T\Downloads\shampoo.pyh.")
print(series.head())
series.plot()
pyplot.show()
"C:\Users\Brindha T\Downloads\Figure_1.png"
series.plot(style='-.')
pyplot.show()
"C:\Users\Brindha T\Downloads\Screenshot_7-9-2024_205328_localhost.jpeg"
series.hist()
pyplot.show()
"C:\Users\Brindha T\Downloads\Screenshot_7-9-2024_205352_localhost.jpeg"
series.plot(kind='kde')
pyplot.show()
"C:\Users\Brindha T\Downloads\Screenshot_7-9-2024_205441_localhost.jpeg"
