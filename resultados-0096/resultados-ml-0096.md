# Reporte de Análisis de Datos - Pandas

`Samuel Martinez Machine Learning pandas, NC 0096`

## 1. DataFrame Convertido
```text
    Estacion  Mes_inicio  Temperatura_C
0  Primavera           3             22
1     Verano           6             30
2      Otoño           9             18
3   Invierno          12             10
4     Lluvia           5             25
5       Seca          11             28
```

## 2.1 Primeras Filas (head)
```text
    Estacion  Mes_inicio  Temperatura_C
0  Primavera           3             22
1     Verano           6             30
```

## 2.2 Últimas Filas (tail)
```text
  Estacion  Mes_inicio  Temperatura_C
4   Lluvia           5             25
5     Seca          11             28
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Estacion           str
Mes_inicio       int64
Temperatura_C    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column         Non-Null Count  Dtype
---  ------         --------------  -----
 0   Estacion       6 non-null      str  
 1   Mes_inicio     6 non-null      int64
 2   Temperatura_C  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de la Columna 'Temperatura_C'
```text
count     6.000000
mean     22.166667
std       7.332576
min      10.000000
25%      19.000000
50%      23.500000
75%      27.250000
max      30.000000
Name: Temperatura_C, dtype: float64
```

## 4. Ordenar Ascendente por Temperatura_C
```text
    Estacion  Mes_inicio  Temperatura_C
3   Invierno          12             10
2      Otoño           9             18
0  Primavera           3             22
4     Lluvia           5             25
5       Seca          11             28
1     Verano           6             30
```

## 5. Ordenar Descendente por Mes_inicio
```text
    Estacion  Mes_inicio  Temperatura_C
3   Invierno          12             10
5       Seca          11             28
2      Otoño           9             18
1     Verano           6             30
4     Lluvia           5             25
0  Primavera           3             22
```

`Samuel Martinez Machine Learning pandas, NC 0096`