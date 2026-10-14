# Reporte de Análisis de Datos - Pandas

`Johan Paulo Machine Learning pandas, NC 0016`

## 1. DataFrame Convertido
```text
        Proyecto  Presupuesto  Integrantes
0            Web        50000            5
1            App        80000            8
2      Marketing        30000            4
3  Investigación       120000           10
4         Diseño        25000            3
5    Consultoría        45000            6
```

## 2.1 Primeras Filas (head)
```text
  Proyecto  Presupuesto  Integrantes
0      Web        50000            5
1      App        80000            8
```

## 2.2 Últimas Filas (tail)
```text
      Proyecto  Presupuesto  Integrantes
4       Diseño        25000            3
5  Consultoría        45000            6
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Proyecto         str
Presupuesto    int64
Integrantes    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column       Non-Null Count  Dtype
---  ------       --------------  -----
 0   Proyecto     6 non-null      str  
 1   Presupuesto  6 non-null      int64
 2   Integrantes  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Presupuesto'
```text
count         6.000000
mean      58333.333333
std       35870.136140
min       25000.000000
25%       33750.000000
50%       47500.000000
75%       72500.000000
max      120000.000000
Name: Presupuesto, dtype: float64
```

## 4. Ordenar Ascendente por Presupuesto
```text
        Proyecto  Presupuesto  Integrantes
4         Diseño        25000            3
2      Marketing        30000            4
5    Consultoría        45000            6
0            Web        50000            5
1            App        80000            8
3  Investigación       120000           10
```

## 5. Ordenar Descendente por Integrantes
```text
        Proyecto  Presupuesto  Integrantes
3  Investigación       120000           10
1            App        80000            8
5    Consultoría        45000            6
0            Web        50000            5
2      Marketing        30000            4
4         Diseño        25000            3
```

`Johan Paulo Machine Learning pandas, NC 0016`