While reading csv you will face an error UnicodeDecodeError
Just do the following step while reading csv file:
```
data = pd.read_csv("/kaggle/input/ann-car-sales-price-prediction/car_purchasing.csv",encoding='ISO-8859-1')
```