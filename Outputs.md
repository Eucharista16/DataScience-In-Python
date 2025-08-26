# Extracted Outputs from Internship Notebook

## Output 1
SNo ObservationDate Province/State  Country/Region  \
0            1      01/22/2020          Anhui  Mainland China   
1            2      01/22/2020        Beijing  Mainland China   
2            3      01/22/2020      Chongqing  Mainland China   
3            4      01/22/2020         Fujian  Mainland China   
4            5      01/22/2020          Gansu  Mainland China   
...        ...             ...            ...             ...   
104256  104257      09/06/2020            NaN         Bahamas   
104257  104258      09/06/2020            NaN         Bahrain   
104258  104259      09/06/2020            NaN      Bangladesh   
104259  104260      09/06/2020            NaN        Barbados   
104260  104261      09/06/2020            NaN         Belarus   

                Last Update  Confirmed  Deaths  Recovered  
0           1/22/2020 17:00        1.0     0.0        0.0  
1           1/22/2020 17:00       14.0     0.0        0.0  
2           1/22/2020 17:00        6.0     0.0        0.0  
3           1/22/2020 17:00        1.0     0.0        0.0  
4           1/22/2020 17:00        0.0     0.0        0.0  
...                     ...        ...     ...        ...  
104256  2021-04-02 15:13:53     2506.0    56.0      948.0  
104257  2021-04-02 15:13:53    55415.0   199.0    50946.0  
104258  2021-04-02 15:13:53   325157.0  4479.0   221275.0  
104259  2021-04-02 15:13:53      178.0     7.0      154.0  
104260     2021-04-02 15:13        NaN     NaN        NaN  

[104261 rows x 8 columns]

## Output 2
Deaths  Recovered
1     0.0        0.0
2     0.0        0.0
3     0.0        0.0

## Output 3
SNo ObservationDate Province/State  Country/Region      Last Update
2    3      01/22/2020      Chongqing  Mainland China  1/22/2020 17:00
3    4      01/22/2020         Fujian  Mainland China  1/22/2020 17:00

## Output 4
SNo ObservationDate Province/State  Country/Region      Last Update  \
0    1      01/22/2020          Anhui  Mainland China  1/22/2020 17:00   
1    2      01/22/2020        Beijing  Mainland China  1/22/2020 17:00   
2    3      01/22/2020      Chongqing  Mainland China  1/22/2020 17:00   
3    4      01/22/2020         Fujian  Mainland China  1/22/2020 17:00   
4    5      01/22/2020          Gansu  Mainland China  1/22/2020 17:00   

   Confirmed  Deaths  Recovered  
0        1.0     0.0        0.0  
1       14.0     0.0        0.0  
2        6.0     0.0        0.0  
3        1.0     0.0        0.0  
4        0.0     0.0        0.0

## Output 5
SNo ObservationDate Province/State Country/Region  \
104256  104257      09/06/2020              0        Bahamas   
104257  104258      09/06/2020              0        Bahrain   
104258  104259      09/06/2020              0     Bangladesh   
104259  104260      09/06/2020              0       Barbados   
104260  104261      09/06/2020              0        Belarus   

                Last Update  Confirmed  Deaths  Recovered  
104256  2021-04-02 15:13:53     2506.0    56.0      948.0  
104257  2021-04-02 15:13:53    55415.0   199.0    50946.0  
104258  2021-04-02 15:13:53   325157.0  4479.0   221275.0  
104259  2021-04-02 15:13:53      178.0     7.0      154.0  
104260     2021-04-02 15:13        0.0     0.0        0.0

## Output 6
SNo ObservationDate Province/State Country/Region  \
21647  21648      05/04/2020            NaN         Panama   
36907  36908      06/06/2020          Skane         Sweden   
94287  94288      08/23/2020       Moquegua           Peru   
70527  70528      07/22/2020     San Martin           Peru   
82476  82477      08/07/2020      Santander       Colombia   
...      ...             ...            ...            ...   
85898  85899      08/12/2020        England             UK   
86644  86645      08/13/2020        England             UK   
87390  87391      08/14/2020        England             UK   
88136  88137      08/15/2020        England             UK   
88882  88883      08/16/2020        England             UK   

               Last Update  Confirmed   Deaths  Recovered  
21647  2020-05-05 02:32:34     7197.0    200.0      641.0  
36907  2021-04-02 15:13:53     1957.0    200.0        0.0  
94287  2021-04-02 15:13:53     7676.0    200.0        0.0  
70527  2021-04-02 15:13:53     7186.0    200.0        0.0  
82476  2021-04-02 15:13:53     5942.0    200.0     1916.0  
...                    ...        ...      ...        ...  
85898  2021-04-02 15:13:53   270971.0  42072.0        0.0  
86644  2021-04-02 15:13:53   270971.0  42072.0        0.0  
87390  2021-04-02 15:13:53   270971.0  42072.0        0.0  
88136  2021-04-02 15:13:53   274248.0  42072.0        0.0  
88882  2021-04-02 15:13:53   275200.0  42072.0        0.0  

[29878 rows x 8 columns]

## Output 7
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 150 entries, 0 to 149
Data columns (total 6 columns):
 #   Column         Non-Null Count  Dtype  
---  ------         --------------  -----  
 0   Id             150 non-null    int64  
 1   SepalLengthCm  148 non-null    float64
 2   SepalWidthCm   147 non-null    float64
 3   PetalLengthCm  144 non-null    float64
 4   PetalWidthCm   150 non-null    float64
 5   Species        150 non-null    object 
dtypes: float64(4), int64(1), object(1)
memory usage: 7.2+ KB
None
Id               0
SepalLengthCm    2
SepalWidthCm     3
PetalLengthCm    6
PetalWidthCm     0
Species          0
dtype: int64
   Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm      Species
0   1            5.1           3.5            1.4           0.2  Iris-setosa
1   2            4.9           3.0            1.4           0.2  Iris-setosa
2   3            4.7           3.2            1.3           0.2  Iris-setosa
3   4            4.6           3.1            1.5           0.2  Iris-setosa
4   5            5.0           3.6            NaN           0.2  Iris-setosa
   Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm      Species
0   1            5.1           3.5            1.4           0.2  Iris-setosa
1   2            4.9           3.0            1.4           0.2  Iris-setosa
2   3            4.7           3.2            1.3           0.2  Iris-setosa
3   4            4.6           3.1            1.5           0.2  Iris-setosa
4   5            5.0           3.6            NaN           0.2  Iris-setosa
   Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm      Species
0   1            5.1           3.5            1.4           0.2  Iris-setosa
1   2            4.9           3.0            1.4           0.2  Iris-setosa
2   3            4.7           3.2            1.3           0.2  Iris-setosa
3   4            4.6           3.1            1.5           0.2  Iris-setosa
4   5            5.0           3.6            1.5           0.2  Iris-setosa
    Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm      Species
0  1.0            5.1           3.5       1.400000           0.2  Iris-setosa
1  2.0            4.9           3.0       1.400000           0.2  Iris-setosa
2  3.0            4.7           3.2       1.300000           0.2  Iris-setosa
3  4.0            4.6           3.1       1.500000           0.2  Iris-setosa
4  5.0            5.0           3.6       3.777778           0.2  Iris-setosa

## Output 8
Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm  \
0      1            5.1           3.5            1.4           0.2   
1      2            4.9           3.0            1.4           0.2   
2      3            4.7           3.2            1.3           0.2   
3      4            4.6           3.1            1.5           0.2   
4      5            5.0           3.6            NaN           0.2   
..   ...            ...           ...            ...           ...   
145  146            6.7           3.0            5.2           2.3   
146  147            6.3           2.5            5.0           1.9   
147  148            6.5           3.0            5.2           2.0   
148  149            6.2           3.4            NaN           2.3   
149  150            5.9           3.0            5.1           1.8   

            Species  
0       Iris-setosa  
1       Iris-setosa  
2       Iris-setosa  
3       Iris-setosa  
4       Iris-setosa  
..              ...  
145  Iris-virginica  
146  Iris-virginica  
147  Iris-virginica  
148  Iris-virginica  
149  Iris-virginica  

[150 rows x 6 columns]
Index(['Id', 'SepalLengthCm', 'SepalWidthCm', 'PetalLengthCm', 'PetalWidthCm',
       'Species'],
      dtype='object')
        Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm  Species
0    False          False         False          False         False    False
1    False          False         False          False         False    False
2    False          False         False          False         False    False
3    False          False         False          False         False    False
4    False          False         False           True         False    False
..     ...            ...           ...            ...           ...      ...
145  False          False         False          False         False    False
146  False          False         False          False         False    False
147  False          False         False          False         False    False
148  False          False         False           True         False    False
149  False          False         False          False         False    False

[150 rows x 6 columns]
Id               0
SepalLengthCm    2
SepalWidthCm     3
PetalLengthCm    6
PetalWidthCm     0
Species          0
dtype: int64
(150, 6)
[5.1        4.9        4.7        4.6        5.         5.4
 4.6        5.         4.4        4.9        5.4        4.8
 4.8        4.3        5.8        5.7        5.4        5.1
 5.7        5.1        5.4        5.1        4.6        5.1
 4.8        5.         5.         5.2        5.2        4.7
 4.8        5.4        5.2        5.5        4.9        5.
 5.5        4.9        4.4        5.1        5.         4.5
 4.4        5.         5.1        4.8        5.1        4.6
 5.3        5.         7.         6.4        6.9        5.5
 6.5        5.7        6.3        4.9        6.6        5.2
 5.         5.9        6.         6.1        5.6        6.7
 5.6        5.8        6.2        5.6        5.9        6.1
 6.3        6.1        6.4        6.6        6.8        6.7
 6.         5.7        5.5        5.5        5.8        6.
 5.4        6.         6.7        6.3        5.6        5.5
 5.5        6.1        5.8        5.         5.6        5.7
 5.7        6.2        5.1        5.7        6.3        5.8
 7.1        6.3        6.5        7.6        4.9        7.3
 6.7        7.2        6.5        5.82702703 6.8        5.7
 5.8        6.4        6.5        7.7        7.7        6.
 6.9        5.6        5.82702703 6.3        6.7        7.2
 6.2        6.1        6.4        7.2        7.4        7.9
 6.4        6.3        6.1        7.7        6.3        6.4
 6.         6.9        6.7        6.9        5.8        6.8
 6.7        6.7        6.3        6.5        6.2        5.9       ]
[3.5        3.         3.2        3.1        3.6        3.9
 3.4        3.4        2.9        3.1        3.7        3.4
 3.         3.         4.         4.4        3.9        3.5
 3.8        3.8        3.4        3.7        3.6        3.3
 3.4        3.         3.4        3.5        3.4        3.2
 3.1        3.4        4.1        4.2        3.1        3.2
 3.5        3.1        3.         3.4        3.5        2.3
 3.2        3.5        3.8        3.         3.8        3.2
 3.7        3.3        3.2        3.2        3.1        2.3
 2.8        2.8        3.3        2.4        2.9        2.7
 2.         3.         2.2        2.9        2.9        3.1
 3.         2.7        2.2        2.5        3.2        2.8
 2.5        2.8        2.9        3.         2.8        3.
 2.9        2.6        2.4        2.4        2.7        2.7
 3.         3.4        3.1        2.3        3.05714286 2.5
 2.6        3.         2.6        2.3        2.7        3.
 2.9        2.9        2.5        2.8        3.3        2.7
 3.         2.9        3.         3.         2.5        2.9
 3.05714286 3.6        3.2        2.7        3.         2.5
 2.8        3.2        3.         3.8        2.6        2.2
 3.2        2.8        2.8        2.7        3.3        3.2
 2.8        3.         2.8        3.         2.8        3.8
 2.8        2.8        2.6        3.         3.4        3.1
 3.         3.1        3.1        3.1        2.7        3.05714286
 3.3        3.         2.5        3.         3.4        3.        ]
[1.4        1.4        1.3        1.5        3.77777778 1.7
 1.4        3.77777778 3.77777778 1.5        1.5        1.6
 1.4        1.1        1.2        1.5        1.3        1.4
 1.7        1.5        1.7        1.5        1.         1.7
 1.9        1.6        1.6        1.5        1.4        1.6
 1.6        1.5        1.5        1.4        1.5        1.2
 1.3        1.5        1.3        1.5        1.3        1.3
 1.3        1.6        1.9        1.4        1.6        1.4
 1.5        1.4        4.7        4.5        4.9        4.
 4.6        4.5        4.7        3.3        4.6        3.9
 3.5        4.2        4.         4.7        3.6        4.4
 4.5        4.1        4.5        3.9        4.8        4.
 4.9        4.7        4.3        4.4        4.8        5.
 4.5        3.5        3.8        3.7        3.9        5.1
 4.5        4.5        4.7        4.4        3.77777778 4.
 4.4        4.6        4.         3.3        4.2        4.2
 4.2        4.3        3.         4.1        6.         5.1
 5.9        5.6        5.8        6.6        4.5        6.3
 5.8        6.1        5.1        5.3        5.5        5.
 5.1        5.3        5.5        6.7        6.9        5.
 5.7        4.9        6.7        4.9        5.7        3.77777778
 4.8        4.9        5.6        5.8        6.1        6.4
 5.6        5.1        5.6        6.1        5.6        5.5
 4.8        5.4        5.6        5.1        5.1        5.9
 5.7        5.2        5.         5.2        3.77777778 5.1       ]
      Id  SepalLengthCm  SepalWidthCm  PetalLengthCm  PetalWidthCm  \
0      1            5.1           3.5       1.400000           0.2   
1      2            4.9           3.0       1.400000           0.2   
2      3            4.7           3.2       1.300000           0.2   
3      4            4.6           3.1       1.500000           0.2   
4      5            5.0           3.6       3.777778           0.2   
..   ...            ...           ...            ...           ...   
145  146            6.7           3.0       5.200000           2.3   
146  147            6.3           2.5       5.000000           1.9   
147  148            6.5           3.0       5.200000           2.0   
148  149            6.2           3.4       3.777778           2.3   
149  150            5.9           3.0       5.100000           1.8   

            Species  
0       Iris-setosa  
1       Iris-setosa  
2       Iris-setosa  
3       Iris-setosa  
4       Iris-setosa  
..              ...  
145  Iris-virginica  
146  Iris-virginica  
147  Iris-virginica  
148  Iris-virginica  
149  Iris-virginica  

[150 rows x 6 columns]
Id               0
SepalLengthCm    0
SepalWidthCm     0
PetalLengthCm    0
PetalWidthCm     0
Species          0
dtype: int64

## Output 9
Imputed X:
[[3 'male' 22.0 1]
 [1 'female' 38.0 1]
 [3 'female' 26.0 0]
 ...
 [3 'female' 24.0 1]
 [1 'male' 26.0 0]
 [3 'male' 32.0 0]]

Encoded y:
[2 0 2 0 2 2 0 2 2 1 2 0 2 2 2 1 2 1 2 2 1 1 2 0 2 2 2 0 2 2 0 0 2 1 0 0 2
 2 2 2 2 1 2 1 2 2 2 2 2 2 2 2 0 1 0 0 1 2 1 2 2 0 0 2 0 2 1 2 2 2 1 2 1 2
 2 2 2 2 1 2 2 2 2 0 1 2 2 2 0 2 2 2 0 2 2 2 0 0 1 1 2 2 0 2 2 2 2 2 2 2 0
 2 2 2 2 2 2 1 0 2 1 2 1 1 0 2 2 2 2 2 2 2 2 1 1 1 0 0 2 0 2 2 2 2 1 1 2 2
 1 1 1 0 2 2 2 0 2 2 2 2 2 1 2 2 2 2 0 2 0 2 0 2 2 2 0 2 2 0 1 2 2 1 2 1 2
 0 2 0 2 2 1 1 2 1 0 0 2 2 2 1 2 2 2 2 2 2 2 2 2 0 2 1 2 1 0 2 1 0 1 2 1 2
 2 0 2 1 2 1 2 0 2 1 2 1 2 1 1 1 1 2 2 1 2 2 0 2 1 0 1 2 2 0 2 2 2 0 0 0 1
 2 2 0 0 2 1 2 2 0 0 0 2 1 0 2 0 2 1 2 2 2 2 2 2 0 2 2 2 1 2 0 0 1 2 2 0 2
 0 0 0 2 2 2 1 2 0 0 0 1 0 0 0 1 2 1 2 1 1 0 0 2 2 1 1 2 0 2 1 2 0 2 0 0 2
 0 2 0 0 2 0 1 0 1 1 1 1 1 2 2 2 2 0 2 2 2 2 0 1 2 2 2 1 2 2 2 2 0 2 2 0 0
 2 2 0 2 0 2 0 2 2 0 2 2 0 2 1 2 1 2 1 0 2 2 0 2 2 2 1 1 1 2 2 2 2 2 1 2 1
 2 2 2 2 0 1 2 2 1 1 1 2 2 2 2 2 2 2 1 1 2 2 0 2 1 2 0 0 2 1 0 1 1 2 2 1 2
 0 1 0 2 0 1 2 0 0 2 2 0 0 1 2 0 2 0 1 2 2 1 0 2 2 2 2 1 1 2 0 1 2 2 2 2 1
 2 2 0 2 0 0 2 2 2 2 0 0 2 2 0 2 0 2 2 2 2 2 0 0 1 0 2 2 2 2 0 0 2 0 1 2 1
 2 0 2 2 0 2 2 1 0 2 1 1 2 2 2 2 1 0 0 2 0 0 2 2 1 0 0 1 1 2 1 0 1 2 2 2 0
 0 0 0 2 2 2 1 2 2 2 2 2 2 2 1 0 0 2 2 2 1 0 2 2 1 0 1 0 2 0 1 0 2 2 2 0 2
 2 1 2 1 2 2 0 1 2 0 2 0 2 0 1 0 2 2 2 2 2 1 2 2 1 1 2 0 2 2 2 0 1 0 2 2 0
 2 0 0 2 1 2 1 2 2 2 0 2 2 2 0 2 0 2 2 2 1 2 2 2 1 2 2 1 0 0 2 0 2 2 1 1 2
 2 0 1 0 1 1 1 2 2 2 2 0 2 0 2 2 1 1 2 2 2 0 0 2 2 2 0 1 2 2 0 2 0 0 2 2 2
 1 1 0 0 2 0 0 0 2 1 2 0 1 2 2 1 2 1 1 0 2 1 2 1 2 0 2 1 1 1 2 2 0 2 2 0 0
 0 2 2 0 2 1 0 2 1 2 2 2 1 1 2 1 2 0 2 2 2 0 2 0 0 2 2 2 2 2 1 2 1 2 2 2 2
 0 2 0 0 2 2 2 2 2 2 0 2 1 2 0 2 1 0 2 2 2 1 1 0 2 2 2 0 2 1 0 2 2 1 2 2 0
 2 1 2 2 0 2 0 2 2 2 2 1 2 0 2 1 2 2 2 0 2 2 2 0 2 1 0 2 2 2 2 2 1 0 2 2 2
 0 1 2 0 0 2 2 2 1 0 2 1 1 1 0 2 2 2 0 0 2 1 2 2 2 2 0 1 2 2 1 2 2 1 0 2 0
 2]

Standardized X:
[[-0.79071393  0.82894596]
 [ 1.26467988 -1.56369352]
 [ 1.26467988  0.82894596]
 ...
 [-0.79071393  0.82894596]
 [ 1.26467988 -1.56369352]
 [-0.79071393  0.82894596]]

## Output 10
array([3, 1, 3, 1, 3, 3, 1, 3, 3, 2, 3, 1, 3, 3, 3, 2, 3, 2, 3, 3, 2, 2,
       3, 1, 3, 3, 3, 1, 3, 3, 1, 1, 3, 2, 1, 1, 3, 3, 3, 3, 3, 2, 3, 2,
       3, 3, 3, 3, 3, 3, 3, 3, 1, 2, 1, 1, 2, 3, 2, 3, 3, 1, 1, 3, 1, 3,
       2, 3, 3, 3, 2, 3, 2, 3, 3, 3, 3, 3, 2, 3, 3, 3, 3, 1, 2, 3, 3, 3,
       1, 3, 3, 3, 1, 3, 3, 3, 1, 1, 2, 2, 3, 3, 1, 3, 3, 3, 3, 3, 3, 3,
       1, 3, 3, 3, 3, 3, 3, 2, 1, 3, 2, 3, 2, 2, 1, 3, 3, 3, 3, 3, 3, 3,
       3, 2, 2, 2, 1, 1, 3, 1, 3, 3, 3, 3, 2, 2, 3, 3, 2, 2, 2, 1, 3, 3,
       3, 1, 3, 3, 3, 3, 3, 2, 3, 3, 3, 3, 1, 3, 1, 3, 1, 3, 3, 3, 1, 3,
       3, 1, 2, 3, 3, 2, 3, 2, 3, 1, 3, 1, 3, 3, 2, 2, 3, 2, 1, 1, 3, 3,
       3, 2, 3, 3, 3, 3, 3, 3, 3, 3, 3, 1, 3, 2, 3, 2, 1, 3, 2, 1, 2, 3,
       2, 3, 3, 1, 3, 2, 3, 2, 3, 1, 3, 2, 3, 2, 3, 2, 2, 2, 2, 3, 3, 2,
       3, 3, 1, 3, 2, 1, 2, 3, 3, 1, 3, 3, 3, 1, 1, 1, 2, 3, 3, 1, 1, 3,
       2, 3, 3, 1, 1, 1, 3, 2, 1, 3, 1, 3, 2, 3, 3, 3, 3, 3, 3, 1, 3, 3,
       3, 2, 3, 1, 1, 2, 3, 3, 1, 3, 1, 1, 1, 3, 3, 3, 2, 3, 1, 1, 1, 2,
       1, 1, 1, 2, 3, 2, 3, 2, 2, 1, 1, 3, 3, 2, 2, 3, 1, 3, 2, 3, 1, 3,
       1, 1, 3, 1, 3, 1, 1, 3, 1, 2, 1, 2, 2, 2, 2, 2, 3, 3, 3, 3, 1, 3,
       3, 3, 3, 1, 2, 3, 3, 3, 2, 3, 3, 3, 3, 1, 3, 3, 1, 1, 3, 3, 1, 3,
       1, 3, 1, 3, 3, 1, 3, 3, 1, 3, 2, 3, 2, 3, 2, 1, 3, 3, 1, 3, 3, 3,
       2, 2, 2, 3, 3, 3, 3, 3, 2, 3, 2, 3, 3, 3, 3, 1, 2, 3, 3, 2, 2, 2,
       3, 3, 3, 3, 3, 3, 3, 2, 2, 3, 3, 1, 3, 2, 3, 1, 1, 3, 2, 1, 2, 2,
       3, 3, 2, 3, 1, 2, 1, 3, 1, 2, 3, 1, 1, 3, 3, 1, 1, 2, 3, 1, 3, 1,
       2, 3, 3, 2, 1, 3, 3, 3, 3, 2, 2, 3, 1, 2, 3, 3, 3, 3, 2, 3, 3, 1,
       3, 1, 1, 3, 3, 3, 3, 1, 1, 3, 3, 1, 3, 1, 3, 3, 3, 3, 3, 1, 1, 2,
       1, 3, 3, 3, 3, 1, 1, 3, 1, 2, 3, 2, 3, 1, 3, 3, 1, 3, 3, 2, 1, 3,
       2, 2, 3, 3, 3, 3, 2, 1, 1, 3, 1, 1, 3, 3, 2, 1, 1, 2, 2, 3, 2, 1,
       2, 3, 3, 3, 1, 1, 1, 1, 3, 3, 3, 2, 3, 3, 3, 3, 3, 3, 3, 2, 1, 1,
       3, 3, 3, 2, 1, 3, 3, 2, 1, 2, 1, 3, 1, 2, 1, 3, 3, 3, 1, 3, 3, 2,
       3, 2, 3, 3, 1, 2, 3, 1, 3, 1, 3, 1, 2, 1, 3, 3, 3, 3, 3, 2, 3, 3,
       2, 2, 3, 1, 3, 3, 3, 1, 2, 1, 3, 3, 1, 3, 1, 1, 3, 2, 3, 2, 3, 3,
       3, 1, 3, 3, 3, 1, 3, 1, 3, 3, 3, 2, 3, 3, 3, 2, 3, 3, 2, 1, 1, 3,
       1, 3, 3, 2, 2, 3, 3, 1, 2, 1, 2, 2, 2, 3, 3, 3, 3, 1, 3, 1, 3, 3,
       2, 2, 3, 3, 3, 1, 1, 3, 3, 3, 1, 2, 3, 3, 1, 3, 1, 1, 3, 3, 3, 2,
       2, 1, 1, 3, 1, 1, 1, 3, 2, 3, 1, 2, 3, 3, 2, 3, 2, 2, 1, 3, 2, 3,
       2, 3, 1, 3, 2, 2, 2, 3, 3, 1, 3, 3, 1, 1, 1, 3, 3, 1, 3, 2, 1, 3,
       2, 3, 3, 3, 2, 2, 3, 2, 3, 1, 3, 3, 3, 1, 3, 1, 1, 3, 3, 3, 3, 3,
       2, 3, 2, 3, 3, 3, 3, 1, 3, 1, 1, 3, 3, 3, 3, 3, 3, 1, 3, 2, 3, 1,
       3, 2, 1, 3, 3, 3, 2, 2, 1, 3, 3, 3, 1, 3, 2, 1, 3, 3, 2, 3, 3, 1,
       3, 2, 3, 3, 1, 3, 1, 3, 3, 3, 3, 2, 3, 1, 3, 2, 3, 3, 3, 1, 3, 3,
       3, 1, 3, 2, 1, 3, 3, 3, 3, 3, 2, 1, 3, 3, 3, 1, 2, 3, 1, 1, 3, 3,
       3, 2, 1, 3, 2, 2, 2, 1, 3, 3, 3, 1, 1, 3, 2, 3, 3, 3, 3, 1, 2, 3,
       3, 2, 3, 3, 2, 1, 3, 1, 3])

## Output 11
[[5.1 3.5 1.4 0.2]
 [4.9 3.  1.4 0.2]
 [4.7 3.2 1.3 0.2]
 [4.6 3.1 1.5 0.2]
 [5.  3.6 1.4 0.2]
 [5.4 3.9 1.7 0.4]
 [4.6 3.4 1.4 0.3]
 [5.  3.4 1.5 0.2]
 [4.4 2.9 1.4 0.2]
 [4.9 3.1 1.5 0.1]
 [5.4 3.7 1.5 0.2]
 [4.8 3.4 1.6 0.2]
 [4.8 3.  1.4 0.1]
 [4.3 3.  1.1 0.1]
 [5.8 4.  1.2 0.2]
 [5.7 4.4 1.5 0.4]
 [5.4 3.9 1.3 0.4]
 [5.1 3.5 1.4 0.3]
 [5.7 3.8 1.7 0.3]
 [5.1 3.8 1.5 0.3]
 [5.4 3.4 1.7 0.2]
 [5.1 3.7 1.5 0.4]
 [4.6 3.6 1.  0.2]
 [5.1 3.3 1.7 0.5]
 [4.8 3.4 1.9 0.2]
 [5.  3.  1.6 0.2]
 [5.  3.4 1.6 0.4]
 [5.2 3.5 1.5 0.2]
 [5.2 3.4 1.4 0.2]
 [4.7 3.2 1.6 0.2]
 [4.8 3.1 1.6 0.2]
 [5.4 3.4 1.5 0.4]
 [5.2 4.1 1.5 0.1]
 [5.5 4.2 1.4 0.2]
 [4.9 3.1 1.5 0.2]
 [5.  3.2 1.2 0.2]
 [5.5 3.5 1.3 0.2]
 [4.9 3.6 1.4 0.1]
 [4.4 3.  1.3 0.2]
 [5.1 3.4 1.5 0.2]
 [5.  3.5 1.3 0.3]
 [4.5 2.3 1.3 0.3]
 [4.4 3.2 1.3 0.2]
 [5.  3.5 1.6 0.6]
 [5.1 3.8 1.9 0.4]
 [4.8 3.  1.4 0.3]
 [5.1 3.8 1.6 0.2]
 [4.6 3.2 1.4 0.2]
 [5.3 3.7 1.5 0.2]
 [5.  3.3 1.4 0.2]
 [7.  3.2 4.7 1.4]
 [6.4 3.2 4.5 1.5]
 [6.9 3.1 4.9 1.5]
 [5.5 2.3 4.  1.3]
 [6.5 2.8 4.6 1.5]
 [5.7 2.8 4.5 1.3]
 [6.3 3.3 4.7 1.6]
 [4.9 2.4 3.3 1. ]
 [6.6 2.9 4.6 1.3]
 [5.2 2.7 3.9 1.4]
 [5.  2.  3.5 1. ]
 [5.9 3.  4.2 1.5]
 [6.  2.2 4.  1. ]
 [6.1 2.9 4.7 1.4]
 [5.6 2.9 3.6 1.3]
 [6.7 3.1 4.4 1.4]
 [5.6 3.  4.5 1.5]
 [5.8 2.7 4.1 1. ]
 [6.2 2.2 4.5 1.5]
 [5.6 2.5 3.9 1.1]
 [5.9 3.2 4.8 1.8]
 [6.1 2.8 4.  1.3]
 [6.3 2.5 4.9 1.5]
 [6.1 2.8 4.7 1.2]
 [6.4 2.9 4.3 1.3]
 [6.6 3.  4.4 1.4]
 [6.8 2.8 4.8 1.4]
 [6.7 3.  5.  1.7]
 [6.  2.9 4.5 1.5]
 [5.7 2.6 3.5 1. ]
 [5.5 2.4 3.8 1.1]
 [5.5 2.4 3.7 1. ]
 [5.8 2.7 3.9 1.2]
 [6.  2.7 5.1 1.6]
 [5.4 3.  4.5 1.5]
 [6.  3.4 4.5 1.6]
 [6.7 3.1 4.7 1.5]
 [6.3 2.3 4.4 1.3]
 [5.6 3.  4.1 1.3]
 [5.5 2.5 4.  1.3]
 [5.5 2.6 4.4 1.2]
 [6.1 3.  4.6 1.4]
 [5.8 2.6 4.  1.2]
 [5.  2.3 3.3 1. ]
 [5.6 2.7 4.2 1.3]
 [5.7 3.  4.2 1.2]
 [5.7 2.9 4.2 1.3]
 [6.2 2.9 4.3 1.3]
 [5.1 2.5 3.  1.1]
 [5.7 2.8 4.1 1.3]
 [6.3 3.3 6.  2.5]
 [5.8 2.7 5.1 1.9]
 [7.1 3.  5.9 2.1]
 [6.3 2.9 5.6 1.8]
 [6.5 3.  5.8 2.2]
 [7.6 3.  6.6 2.1]
 [4.9 2.5 4.5 1.7]
 [7.3 2.9 6.3 1.8]
 [6.7 2.5 5.8 1.8]
 [7.2 3.6 6.1 2.5]
 [6.5 3.2 5.1 2. ]
 [6.4 2.7 5.3 1.9]
 [6.8 3.  5.5 2.1]
 [5.7 2.5 5.  2. ]
 [5.8 2.8 5.1 2.4]
 [6.4 3.2 5.3 2.3]
 [6.5 3.  5.5 1.8]
 [7.7 3.8 6.7 2.2]
 [7.7 2.6 6.9 2.3]
 [6.  2.2 5.  1.5]
 [6.9 3.2 5.7 2.3]
 [5.6 2.8 4.9 2. ]
 [7.7 2.8 6.7 2. ]
 [6.3 2.7 4.9 1.8]
 [6.7 3.3 5.7 2.1]
 [7.2 3.2 6.  1.8]
 [6.2 2.8 4.8 1.8]
 [6.1 3.  4.9 1.8]
 [6.4 2.8 5.6 2.1]
 [7.2 3.  5.8 1.6]
 [7.4 2.8 6.1 1.9]
 [7.9 3.8 6.4 2. ]
 [6.4 2.8 5.6 2.2]
 [6.3 2.8 5.1 1.5]
 [6.1 2.6 5.6 1.4]
 [7.7 3.  6.1 2.3]
 [6.3 3.4 5.6 2.4]
 [6.4 3.1 5.5 1.8]
 [6.  3.  4.8 1.8]
 [6.9 3.1 5.4 2.1]
 [6.7 3.1 5.6 2.4]
 [6.9 3.1 5.1 2.3]
 [5.8 2.7 5.1 1.9]
 [6.8 3.2 5.9 2.3]
 [6.7 3.3 5.7 2.5]
 [6.7 3.  5.2 2.3]
 [6.3 2.5 5.  1.9]
 [6.5 3.  5.2 2. ]
 [6.2 3.4 5.4 2.3]
 [5.9 3.  5.1 1.8]]
[0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0
 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1
 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 2 2 2 2 2 2 2 2 2 2 2
 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2 2
 2 2]

## Output 12
GaussianNB()

## Output 13
array([2, 2, 2, 2, 2, 1, 2, 0, 0, 0, 0, 1, 2, 0, 1, 2, 0, 0, 2, 1, 0, 1,
       1, 2, 1, 0, 0, 1, 2, 2])

## Output 14
1.0

## Output 15
Accuracy: 1.0

## Output 16
array([0])

## Output 17
car_ID  symboling                   CarName fueltype aspiration doornumber  \
0       1          3        alfa-romero giulia      gas        std        two   
1       2          3       alfa-romero stelvio      gas        std        two   
2       3          1  alfa-romero Quadrifoglio      gas        std        two   
3       4          2               audi 100 ls      gas        std       four   
4       5          2                audi 100ls      gas        std       four   

       carbody drivewheel enginelocation  wheelbase  ...  enginesize  \
0  convertible        rwd          front       88.6  ...         130   
1  convertible        rwd          front       88.6  ...         130   
2    hatchback        rwd          front       94.5  ...         152   
3        sedan        fwd          front       99.8  ...         109   
4        sedan        4wd          front       99.4  ...         136   

   fuelsystem  boreratio  stroke compressionratio horsepower  peakrpm citympg  \
0        mpfi       3.47    2.68              9.0        111     5000      21   
1        mpfi       3.47    2.68              9.0        111     5000      21   
2        mpfi       2.68    3.47              9.0        154     5000      19   
3        mpfi       3.19    3.40             10.0        102     5500      24   
4        mpfi       3.19    3.40              8.0        115     5500      18   

   highwaympg    price  
0          27  13495.0  
1          27  16500.0  
2          26  16500.0  
3          30  13950.0  
4          22  17450.0  

[5 rows x 26 columns]

## Output 18
Column names: Index(['Age', 'Premium'], dtype='object')
First few rows of data:
    Age  Premium
0   18    10000
1   22    15000
2   23    18000
3   26    21000
4   28    24000
X values: [18 22 23 26 28 31 33]
y values: [10000 15000 18000 21000 24000 26500 27000]

## Output 19
LinearRegression()

## Output 20
MSE: 0.07700402959637515

## Output 21
LogisticRegression()

## Output 22
Accuracy: 0.0

## Output 23
array(['mitsubishi mirage g4'], dtype=object)

## Output 24
DecisionTreeClassifier(random_state=23)

## Output 25
Accuracy: 1.0

## Output 26
array([0])

## Output 27
(205, 1)
(205,)

## Output 28
DecisionTreeRegressor(random_state=42)

## Output 29
MSE: 1037.4854000377466

## Output 30
RandomForestClassifier()

## Output 31
Accuracy: 0.9

## Output 32
(205, 1)
(205,)
Accuracy: 0.04878048780487805

## Output 33
Age  Gender    Education Level              Job Title  \
0     32.0    Male         Bachelor's      Software Engineer   
1     28.0  Female           Master's           Data Analyst   
2     45.0    Male                PhD         Senior Manager   
3     36.0  Female         Bachelor's        Sales Associate   
4     52.0    Male           Master's               Director   
...    ...     ...                ...                    ...   
6699  49.0  Female                PhD  Director of Marketing   
6700  32.0    Male        High School        Sales Associate   
6701  30.0  Female  Bachelor's Degree      Financial Manager   
6702  46.0    Male    Master's Degree      Marketing Manager   
6703  26.0  Female        High School        Sales Executive   

      Years of Experience    Salary  
0                     5.0   90000.0  
1                     3.0   65000.0  
2                    15.0  150000.0  
3                     7.0   60000.0  
4                    20.0  200000.0  
...                   ...       ...  
6699                 20.0  200000.0  
6700                  3.0   50000.0  
6701                  4.0   55000.0  
6702                 14.0  140000.0  
6703                  1.0   35000.0  

[6704 rows x 6 columns]

## Output 34
ExtraTreesClassifier(bootstrap=False, ccp_alpha=0.0, class_weight=None,
                     criterion='gini', max_depth=None, max_features='sqrt',
                     max_leaf_nodes=None, max_samples=None,
                     min_impurity_decrease=0.0, min_samples_leaf=1,
                     min_samples_split=2, min_weight_fraction_leaf=0.0,
                     monotonic_cst=None, n_estimators=100, n_jobs=-1,
                     oob_score=False, random_state=1897, verbose=0,
                     warm_start=False)

## Output 35
LinearRegression(copy_X=True, fit_intercept=True, n_jobs=-1, positive=False)

## Output 36
car_ID  symboling                   CarName fueltype aspiration  \
0         1          3        alfa-romero giulia      gas        std   
1         2          3       alfa-romero stelvio      gas        std   
2         3          1  alfa-romero Quadrifoglio      gas        std   
3         4          2               audi 100 ls      gas        std   
4         5          2                audi 100ls      gas        std   
..      ...        ...                       ...      ...        ...   
200     201         -1           volvo 145e (sw)      gas        std   
201     202         -1               volvo 144ea      gas      turbo   
202     203         -1               volvo 244dl      gas        std   
203     204         -1                 volvo 246   diesel      turbo   
204     205         -1               volvo 264gl      gas      turbo   

    doornumber      carbody drivewheel enginelocation   wheelbase  ...  \
0          two  convertible        rwd          front   88.599998  ...   
1          two  convertible        rwd          front   88.599998  ...   
2          two    hatchback        rwd          front   94.500000  ...   
3         four        sedan        fwd          front   99.800003  ...   
4         four        sedan        4wd          front   99.400002  ...   
..         ...          ...        ...            ...         ...  ...   
200       four        sedan        rwd          front  109.099998  ...   
201       four        sedan        rwd          front  109.099998  ...   
202       four        sedan        rwd          front  109.099998  ...   
203       four        sedan        rwd          front  109.099998  ...   
204       four        sedan        rwd          front  109.099998  ...   

     fuelsystem  boreratio  stroke  compressionratio horsepower peakrpm  \
0          mpfi       3.47    2.68               9.0        111    5000   
1          mpfi       3.47    2.68               9.0        111    5000   
2          mpfi       2.68    3.47               9.0        154    5000   
3          mpfi       3.19    3.40              10.0        102    5500   
4          mpfi       3.19    3.40               8.0        115    5500   
..          ...        ...     ...               ...        ...     ...   
200        mpfi       3.78    3.15               9.5        114    5400   
201        mpfi       3.78    3.15               8.7        160    5300   
202        mpfi       3.58    2.87               8.8        134    5500   
203         idi       3.01    3.40              23.0        106    4800   
204        mpfi       3.78    3.15               9.5        114    5400   

     citympg highwaympg    price  prediction_label  
0         21         27  13495.0      14367.495071  
1         21         27  16500.0      16116.103774  
2         19         26  16500.0      15893.860912  
3         24         30  13950.0      13395.482956  
4         18         22  17450.0      17468.445805  
..       ...        ...      ...               ...  
200       23         28  16845.0      16156.315376  
201       19         25  19045.0      20336.867426  
202       18         23  21485.0      20869.458235  
203       26         27  22470.0      23471.840592  
204       19         25  22625.0      21134.614436  

[205 rows x 27 columns]

## Output 37
survived  pclass     sex   age  sibsp  parch     fare embarked   class  \
0           0       3    male  22.0      1      0   7.2500        S   Third   
1           1       1  female  38.0      1      0  71.2833        C   First   
2           1       3  female  26.0      0      0   7.9250        S   Third   
3           1       1  female  35.0      1      0  53.1000        S   First   
4           0       3    male  35.0      0      0   8.0500        S   Third   
..        ...     ...     ...   ...    ...    ...      ...      ...     ...   
884         0       2    male  27.0      0      0  13.0000        S  Second   
885         1       1  female  19.0      0      0  30.0000        S   First   
886         0       3  female   NaN      1      2  23.4500        S   Third   
887         1       1    male  26.0      0      0  30.0000        C   First   
888         0       3    male  32.0      0      0   7.7500        Q   Third   

       who  adult_male deck  embark_town alive  alone  
0      man        True  NaN  Southampton    no  False  
1    woman       False    C    Cherbourg   yes  False  
2    woman       False  NaN  Southampton   yes   True  
3    woman       False    C  Southampton   yes  False  
4      man        True  NaN  Southampton    no   True  
..     ...         ...  ...          ...   ...    ...  
884    man        True  NaN  Southampton    no   True  
885  woman       False    B  Southampton   yes   True  
886  woman       False  NaN  Southampton    no  False  
887    man        True    C    Cherbourg   yes   True  
888    man        True  NaN   Queenstown    no   True  

[889 rows x 15 columns]

## Output 38
LogisticRegression(C=1.0, class_weight=None, dual=False, fit_intercept=True,
                   intercept_scaling=1, l1_ratio=None, max_iter=1000,
                   multi_class='auto', n_jobs=None, penalty='l2',
                   random_state=7220, solver='lbfgs', tol=0.0001, verbose=0,
                   warm_start=False)

## Output 39
survived  pclass     sex   age  sibsp  parch       fare embarked   class  \
0           0       3    male  22.0      1      0   7.250000        S   Third   
1           1       1  female  38.0      1      0  71.283302        C   First   
2           1       3  female  26.0      0      0   7.925000        S   Third   
3           1       1  female  35.0      1      0  53.099998        S   First   
4           0       3    male  35.0      0      0   8.050000        S   Third   
..        ...     ...     ...   ...    ...    ...        ...      ...     ...   
884         0       2    male  27.0      0      0  13.000000        S  Second   
885         1       1  female  19.0      0      0  30.000000        S   First   
886         0       3  female   NaN      1      2  23.450001        S   Third   
887         1       1    male  26.0      0      0  30.000000        C   First   
888         0       3    male  32.0      0      0   7.750000        Q   Third   

       who  adult_male deck  embark_town alive  alone  prediction_label  \
0      man        True  NaN  Southampton    no  False                 0   
1    woman       False    C    Cherbourg   yes  False                 0   
2    woman       False  NaN  Southampton   yes   True                 1   
3    woman       False    C  Southampton   yes  False                 0   
4      man        True  NaN  Southampton    no   True                 1   
..     ...         ...  ...          ...   ...    ...               ...   
884    man        True  NaN  Southampton    no   True                 1   
885  woman       False    B  Southampton   yes   True                 1   
886  woman       False  NaN  Southampton    no  False                 0   
887    man        True    C    Cherbourg   yes   True                 1   
888    man        True  NaN   Queenstown    no   True                 1   

     prediction_score  
0              0.8786  
1              0.9668  
2              0.9699  
3              0.9521  
4              0.9832  
..                ...  
884            0.9744  
885            0.9443  
886            1.0000  
887            0.9613  
888            0.9845  

[889 rows x 17 columns]

## Output 40
Requirement already satisfied: torch in /usr/local/lib/python3.10/dist-packages (2.3.0+cu121)
Requirement already satisfied: filelock in /usr/local/lib/python3.10/dist-packages (from torch) (3.15.3)
Requirement already satisfied: typing-extensions>=4.8.0 in /usr/local/lib/python3.10/dist-packages (from torch) (4.12.2)
Requirement already satisfied: sympy in /usr/local/lib/python3.10/dist-packages (from torch) (1.12.1)
Requirement already satisfied: networkx in /usr/local/lib/python3.10/dist-packages (from torch) (3.3)
Requirement already satisfied: jinja2 in /usr/local/lib/python3.10/dist-packages (from torch) (3.1.4)
Requirement already satisfied: fsspec in /usr/local/lib/python3.10/dist-packages (from torch) (2023.6.0)
Collecting nvidia-cuda-nvrtc-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_nvrtc_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (23.7 MB)
Collecting nvidia-cuda-runtime-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_runtime_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (823 kB)
Collecting nvidia-cuda-cupti-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_cupti_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (14.1 MB)
Collecting nvidia-cudnn-cu12==8.9.2.26 (from torch)
  Using cached nvidia_cudnn_cu12-8.9.2.26-py3-none-manylinux1_x86_64.whl (731.7 MB)
Collecting nvidia-cublas-cu12==12.1.3.1 (from torch)
  Using cached nvidia_cublas_cu12-12.1.3.1-py3-none-manylinux1_x86_64.whl (410.6 MB)
Collecting nvidia-cufft-cu12==11.0.2.54 (from torch)
  Using cached nvidia_cufft_cu12-11.0.2.54-py3-none-manylinux1_x86_64.whl (121.6 MB)
Collecting nvidia-curand-cu12==10.3.2.106 (from torch)
  Using cached nvidia_curand_cu12-10.3.2.106-py3-none-manylinux1_x86_64.whl (56.5 MB)
Collecting nvidia-cusolver-cu12==11.4.5.107 (from torch)
  Using cached nvidia_cusolver_cu12-11.4.5.107-py3-none-manylinux1_x86_64.whl (124.2 MB)
Collecting nvidia-cusparse-cu12==12.1.0.106 (from torch)
  Using cached nvidia_cusparse_cu12-12.1.0.106-py3-none-manylinux1_x86_64.whl (196.0 MB)
Collecting nvidia-nccl-cu12==2.20.5 (from torch)
  Using cached nvidia_nccl_cu12-2.20.5-py3-none-manylinux2014_x86_64.whl (176.2 MB)
Collecting nvidia-nvtx-cu12==12.1.105 (from torch)
  Using cached nvidia_nvtx_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (99 kB)
Requirement already satisfied: triton==2.3.0 in /usr/local/lib/python3.10/dist-packages (from torch) (2.3.0)
Collecting nvidia-nvjitlink-cu12 (from nvidia-cusolver-cu12==11.4.5.107->torch)
  Downloading nvidia_nvjitlink_cu12-12.5.40-py3-none-manylinux2014_x86_64.whl (21.3 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m21.3/21.3 MB[0m [31m45.9 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.10/dist-packages (from jinja2->torch) (2.1.5)
Requirement already satisfied: mpmath<1.4.0,>=1.1.0 in /usr/local/lib/python3.10/dist-packages (from sympy->torch) (1.3.0)
Installing collected packages: nvidia-nvtx-cu12, nvidia-nvjitlink-cu12, nvidia-nccl-cu12, nvidia-curand-cu12, nvidia-cufft-cu12, nvidia-cuda-runtime-cu12, nvidia-cuda-nvrtc-cu12, nvidia-cuda-cupti-cu12, nvidia-cublas-cu12, nvidia-cusparse-cu12, nvidia-cudnn-cu12, nvidia-cusolver-cu12
Successfully installed nvidia-cublas-cu12-12.1.3.1 nvidia-cuda-cupti-cu12-12.1.105 nvidia-cuda-nvrtc-cu12-12.1.105 nvidia-cuda-runtime-cu12-12.1.105 nvidia-cudnn-cu12-8.9.2.26 nvidia-cufft-cu12-11.0.2.54 nvidia-curand-cu12-10.3.2.106 nvidia-cusolver-cu12-11.4.5.107 nvidia-cusparse-cu12-12.1.0.106 nvidia-nccl-cu12-2.20.5 nvidia-nvjitlink-cu12-12.5.40 nvidia-nvtx-cu12-12.1.105

## Output 41
tensor([[5.1000, 3.5000, 1.4000, 0.2000]])

## Output 42
Collecting pycaret
  Downloading pycaret-3.3.2-py3-none-any.whl (486 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m486.1/486.1 kB[0m [31m6.4 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: ipython>=5.5.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (7.34.0)
Requirement already satisfied: ipywidgets>=7.6.5 in /usr/local/lib/python3.10/dist-packages (from pycaret) (7.7.1)
Requirement already satisfied: tqdm>=4.62.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (4.66.4)
Requirement already satisfied: numpy<1.27,>=1.21 in /usr/local/lib/python3.10/dist-packages (from pycaret) (1.25.2)
Requirement already satisfied: pandas<2.2.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (2.0.3)
Requirement already satisfied: jinja2>=3 in /usr/local/lib/python3.10/dist-packages (from pycaret) (3.1.4)
Requirement already satisfied: scipy<=1.11.4,>=1.6.1 in /usr/local/lib/python3.10/dist-packages (from pycaret) (1.11.4)
Collecting joblib<1.4,>=1.2.0 (from pycaret)
  Downloading joblib-1.3.2-py3-none-any.whl (302 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m302.2/302.2 kB[0m [31m24.1 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting scikit-learn>1.4.0 (from pycaret)
  Downloading scikit_learn-1.5.0-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (13.3 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m13.3/13.3 MB[0m [31m44.7 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting pyod>=1.1.3 (from pycaret)
  Downloading pyod-2.0.1.tar.gz (163 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m163.8/163.8 kB[0m [31m18.8 MB/s[0m eta [36m0:00:00[0m
[?25h  Preparing metadata (setup.py) ... [?25l[?25hdone
Collecting imbalanced-learn>=0.12.0 (from pycaret)
  Downloading imbalanced_learn-0.12.3-py3-none-any.whl (258 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m258.3/258.3 kB[0m [31m26.3 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting category-encoders>=2.4.0 (from pycaret)
  Downloading category_encoders-2.6.3-py2.py3-none-any.whl (81 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m81.9/81.9 kB[0m [31m5.5 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: lightgbm>=3.0.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (4.1.0)
Requirement already satisfied: numba>=0.55.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (0.58.1)
Requirement already satisfied: requests>=2.27.1 in /usr/local/lib/python3.10/dist-packages (from pycaret) (2.31.0)
Requirement already satisfied: psutil>=5.9.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (5.9.5)
Requirement already satisfied: markupsafe>=2.0.1 in /usr/local/lib/python3.10/dist-packages (from pycaret) (2.1.5)
Requirement already satisfied: importlib-metadata>=4.12.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (7.2.0)
Requirement already satisfied: nbformat>=4.2.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (5.10.4)
Requirement already satisfied: cloudpickle in /usr/local/lib/python3.10/dist-packages (from pycaret) (2.2.1)
Collecting deprecation>=2.1.0 (from pycaret)
  Downloading deprecation-2.1.0-py2.py3-none-any.whl (11 kB)
Collecting xxhash (from pycaret)
  Downloading xxhash-3.4.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (194 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m194.1/194.1 kB[0m [31m19.4 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: matplotlib<3.8.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (3.7.1)
Collecting scikit-plot>=0.3.7 (from pycaret)
  Downloading scikit_plot-0.3.7-py3-none-any.whl (33 kB)
Requirement already satisfied: yellowbrick>=1.4 in /usr/local/lib/python3.10/dist-packages (from pycaret) (1.5)
Requirement already satisfied: plotly>=5.14.0 in /usr/local/lib/python3.10/dist-packages (from pycaret) (5.15.0)
Collecting kaleido>=0.2.1 (from pycaret)
  Downloading kaleido-0.2.1-py2.py3-none-manylinux1_x86_64.whl (79.9 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m79.9/79.9 MB[0m [31m9.7 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting schemdraw==0.15 (from pycaret)
  Downloading schemdraw-0.15-py3-none-any.whl (106 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m106.8/106.8 kB[0m [31m12.0 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting plotly-resampler>=0.8.3.1 (from pycaret)
  Downloading plotly_resampler-0.10.0-py3-none-any.whl (80 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m80.7/80.7 kB[0m [31m10.4 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: statsmodels>=0.12.1 in /usr/local/lib/python3.10/dist-packages (from pycaret) (0.14.2)
Collecting sktime==0.26.0 (from pycaret)
  Downloading sktime-0.26.0-py3-none-any.whl (21.8 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m21.8/21.8 MB[0m [31m57.4 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting tbats>=1.1.3 (from pycaret)
  Downloading tbats-1.1.3-py3-none-any.whl (44 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m44.0/44.0 kB[0m [31m5.8 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting pmdarima>=2.0.4 (from pycaret)
  Downloading pmdarima-2.0.4-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.manylinux_2_28_x86_64.whl (2.1 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m2.1/2.1 MB[0m [31m69.0 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting wurlitzer (from pycaret)
  Downloading wurlitzer-3.1.1-py3-none-any.whl (8.6 kB)
Requirement already satisfied: packaging in /usr/local/lib/python3.10/dist-packages (from sktime==0.26.0->pycaret) (24.1)
Collecting scikit-base<0.8.0 (from sktime==0.26.0->pycaret)
  Downloading scikit_base-0.7.8-py3-none-any.whl (130 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m130.1/130.1 kB[0m [31m14.0 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting scikit-learn>1.4.0 (from pycaret)
  Downloading scikit_learn-1.4.2-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (12.1 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m12.1/12.1 MB[0m [31m77.7 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: patsy>=0.5.1 in /usr/local/lib/python3.10/dist-packages (from category-encoders>=2.4.0->pycaret) (0.5.6)
Requirement already satisfied: threadpoolctl>=2.0.0 in /usr/local/lib/python3.10/dist-packages (from imbalanced-learn>=0.12.0->pycaret) (3.5.0)
Requirement already satisfied: zipp>=0.5 in /usr/local/lib/python3.10/dist-packages (from importlib-metadata>=4.12.0->pycaret) (3.19.2)
Requirement already satisfied: setuptools>=18.5 in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (67.7.2)
Collecting jedi>=0.16 (from ipython>=5.5.0->pycaret)
  Downloading jedi-0.19.1-py2.py3-none-any.whl (1.6 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m1.6/1.6 MB[0m [31m62.2 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: decorator in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (4.4.2)
Requirement already satisfied: pickleshare in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (0.7.5)
Requirement already satisfied: traitlets>=4.2 in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (5.7.1)
Requirement already satisfied: prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0 in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (3.0.47)
Requirement already satisfied: pygments in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (2.16.1)
Requirement already satisfied: backcall in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (0.2.0)
Requirement already satisfied: matplotlib-inline in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (0.1.7)
Requirement already satisfied: pexpect>4.3 in /usr/local/lib/python3.10/dist-packages (from ipython>=5.5.0->pycaret) (4.9.0)
Requirement already satisfied: ipykernel>=4.5.1 in /usr/local/lib/python3.10/dist-packages (from ipywidgets>=7.6.5->pycaret) (5.5.6)
Requirement already satisfied: ipython-genutils~=0.2.0 in /usr/local/lib/python3.10/dist-packages (from ipywidgets>=7.6.5->pycaret) (0.2.0)
Requirement already satisfied: widgetsnbextension~=3.6.0 in /usr/local/lib/python3.10/dist-packages (from ipywidgets>=7.6.5->pycaret) (3.6.6)
Requirement already satisfied: jupyterlab-widgets>=1.0.0 in /usr/local/lib/python3.10/dist-packages (from ipywidgets>=7.6.5->pycaret) (3.0.11)
Requirement already satisfied: contourpy>=1.0.1 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (1.2.1)
Requirement already satisfied: cycler>=0.10 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (0.12.1)
Requirement already satisfied: fonttools>=4.22.0 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (4.53.0)
Requirement already satisfied: kiwisolver>=1.0.1 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (1.4.5)
Requirement already satisfied: pillow>=6.2.0 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (9.4.0)
Requirement already satisfied: pyparsing>=2.3.1 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (3.1.2)
Requirement already satisfied: python-dateutil>=2.7 in /usr/local/lib/python3.10/dist-packages (from matplotlib<3.8.0->pycaret) (2.8.2)
Requirement already satisfied: fastjsonschema>=2.15 in /usr/local/lib/python3.10/dist-packages (from nbformat>=4.2.0->pycaret) (2.20.0)
Requirement already satisfied: jsonschema>=2.6 in /usr/local/lib/python3.10/dist-packages (from nbformat>=4.2.0->pycaret) (4.19.2)
Requirement already satisfied: jupyter-core!=5.0.*,>=4.12 in /usr/local/lib/python3.10/dist-packages (from nbformat>=4.2.0->pycaret) (5.7.2)
Requirement already satisfied: llvmlite<0.42,>=0.41.0dev0 in /usr/local/lib/python3.10/dist-packages (from numba>=0.55.0->pycaret) (0.41.1)
Requirement already satisfied: pytz>=2020.1 in /usr/local/lib/python3.10/dist-packages (from pandas<2.2.0->pycaret) (2023.4)
Requirement already satisfied: tzdata>=2022.1 in /usr/local/lib/python3.10/dist-packages (from pandas<2.2.0->pycaret) (2024.1)
Requirement already satisfied: tenacity>=6.2.0 in /usr/local/lib/python3.10/dist-packages (from plotly>=5.14.0->pycaret) (8.4.1)
Collecting dash>=2.9.0 (from plotly-resampler>=0.8.3.1->pycaret)
  Downloading dash-2.17.1-py3-none-any.whl (7.5 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m7.5/7.5 MB[0m [31m83.3 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting orjson<4.0.0,>=3.8.0 (from plotly-resampler>=0.8.3.1->pycaret)
  Downloading orjson-3.10.5-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (144 kB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m145.0/145.0 kB[0m [31m16.6 MB/s[0m eta [36m0:00:00[0m
[?25hCollecting tsdownsample>=0.1.3 (from plotly-resampler>=0.8.3.1->pycaret)
  Downloading tsdownsample-0.1.3-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (2.1 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m2.1/2.1 MB[0m [31m81.2 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: Cython!=0.29.18,!=0.29.31,>=0.29 in /usr/local/lib/python3.10/dist-packages (from pmdarima>=2.0.4->pycaret) (3.0.10)
Requirement already satisfied: urllib3 in /usr/local/lib/python3.10/dist-packages (from pmdarima>=2.0.4->pycaret) (2.0.7)
Requirement already satisfied: charset-normalizer<4,>=2 in /usr/local/lib/python3.10/dist-packages (from requests>=2.27.1->pycaret) (3.3.2)
Requirement already satisfied: idna<4,>=2.5 in /usr/local/lib/python3.10/dist-packages (from requests>=2.27.1->pycaret) (3.7)
Requirement already satisfied: certifi>=2017.4.17 in /usr/local/lib/python3.10/dist-packages (from requests>=2.27.1->pycaret) (2024.6.2)
Requirement already satisfied: Flask<3.1,>=1.0.4 in /usr/local/lib/python3.10/dist-packages (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret) (2.2.5)
Requirement already satisfied: Werkzeug<3.1 in /usr/local/lib/python3.10/dist-packages (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret) (3.0.3)
Collecting dash-html-components==2.0.0 (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret)
  Downloading dash_html_components-2.0.0-py3-none-any.whl (4.1 kB)
Collecting dash-core-components==2.0.0 (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret)
  Downloading dash_core_components-2.0.0-py3-none-any.whl (3.8 kB)
Collecting dash-table==5.0.0 (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret)
  Downloading dash_table-5.0.0-py3-none-any.whl (3.9 kB)
Requirement already satisfied: typing-extensions>=4.1.1 in /usr/local/lib/python3.10/dist-packages (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret) (4.12.2)
Collecting retrying (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret)
  Downloading retrying-1.3.4-py3-none-any.whl (11 kB)
Requirement already satisfied: nest-asyncio in /usr/local/lib/python3.10/dist-packages (from dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret) (1.6.0)
Requirement already satisfied: jupyter-client in /usr/local/lib/python3.10/dist-packages (from ipykernel>=4.5.1->ipywidgets>=7.6.5->pycaret) (6.1.12)
Requirement already satisfied: tornado>=4.2 in /usr/local/lib/python3.10/dist-packages (from ipykernel>=4.5.1->ipywidgets>=7.6.5->pycaret) (6.3.3)
Requirement already satisfied: parso<0.9.0,>=0.8.3 in /usr/local/lib/python3.10/dist-packages (from jedi>=0.16->ipython>=5.5.0->pycaret) (0.8.4)
Requirement already satisfied: attrs>=22.2.0 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=4.2.0->pycaret) (23.2.0)
Requirement already satisfied: jsonschema-specifications>=2023.03.6 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=4.2.0->pycaret) (2023.12.1)
Requirement already satisfied: referencing>=0.28.4 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=4.2.0->pycaret) (0.35.1)
Requirement already satisfied: rpds-py>=0.7.1 in /usr/local/lib/python3.10/dist-packages (from jsonschema>=2.6->nbformat>=4.2.0->pycaret) (0.18.1)
Requirement already satisfied: platformdirs>=2.5 in /usr/local/lib/python3.10/dist-packages (from jupyter-core!=5.0.*,>=4.12->nbformat>=4.2.0->pycaret) (4.2.2)
Requirement already satisfied: six in /usr/local/lib/python3.10/dist-packages (from patsy>=0.5.1->category-encoders>=2.4.0->pycaret) (1.16.0)
Requirement already satisfied: ptyprocess>=0.5 in /usr/local/lib/python3.10/dist-packages (from pexpect>4.3->ipython>=5.5.0->pycaret) (0.7.0)
Requirement already satisfied: wcwidth in /usr/local/lib/python3.10/dist-packages (from prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0->ipython>=5.5.0->pycaret) (0.2.13)
Requirement already satisfied: notebook>=4.4.1 in /usr/local/lib/python3.10/dist-packages (from widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (6.5.5)
Requirement already satisfied: itsdangerous>=2.0 in /usr/local/lib/python3.10/dist-packages (from Flask<3.1,>=1.0.4->dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret) (2.2.0)
Requirement already satisfied: click>=8.0 in /usr/local/lib/python3.10/dist-packages (from Flask<3.1,>=1.0.4->dash>=2.9.0->plotly-resampler>=0.8.3.1->pycaret) (8.1.7)
Requirement already satisfied: pyzmq<25,>=17 in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (24.0.1)
Requirement already satisfied: argon2-cffi in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (23.1.0)
Requirement already satisfied: nbconvert>=5 in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (6.5.4)
Requirement already satisfied: Send2Trash>=1.8.0 in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.8.3)
Requirement already satisfied: terminado>=0.8.3 in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.18.1)
Requirement already satisfied: prometheus-client in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.20.0)
Requirement already satisfied: nbclassic>=0.4.7 in /usr/local/lib/python3.10/dist-packages (from notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.1.0)
Requirement already satisfied: notebook-shim>=0.2.3 in /usr/local/lib/python3.10/dist-packages (from nbclassic>=0.4.7->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.2.4)
Requirement already satisfied: lxml in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (4.9.4)
Requirement already satisfied: beautifulsoup4 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (4.12.3)
Requirement already satisfied: bleach in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (6.1.0)
Requirement already satisfied: defusedxml in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.7.1)
Requirement already satisfied: entrypoints>=0.2.2 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.4)
Requirement already satisfied: jupyterlab-pygments in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.3.0)
Requirement already satisfied: mistune<2,>=0.8.1 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.8.4)
Requirement already satisfied: nbclient>=0.5.0 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.10.0)
Requirement already satisfied: pandocfilters>=1.4.1 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.5.1)
Requirement already satisfied: tinycss2 in /usr/local/lib/python3.10/dist-packages (from nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.3.0)
Requirement already satisfied: argon2-cffi-bindings in /usr/local/lib/python3.10/dist-packages (from argon2-cffi->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (21.2.0)
Requirement already satisfied: jupyter-server<3,>=1.8 in /usr/local/lib/python3.10/dist-packages (from notebook-shim>=0.2.3->nbclassic>=0.4.7->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.24.0)
Requirement already satisfied: cffi>=1.0.1 in /usr/local/lib/python3.10/dist-packages (from argon2-cffi-bindings->argon2-cffi->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.16.0)
Requirement already satisfied: soupsieve>1.2 in /usr/local/lib/python3.10/dist-packages (from beautifulsoup4->nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (2.5)
Requirement already satisfied: webencodings in /usr/local/lib/python3.10/dist-packages (from bleach->nbconvert>=5->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (0.5.1)
Requirement already satisfied: pycparser in /usr/local/lib/python3.10/dist-packages (from cffi>=1.0.1->argon2-cffi-bindings->argon2-cffi->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (2.22)
Requirement already satisfied: anyio<4,>=3.1.0 in /usr/local/lib/python3.10/dist-packages (from jupyter-server<3,>=1.8->notebook-shim>=0.2.3->nbclassic>=0.4.7->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (3.7.1)
Requirement already satisfied: websocket-client in /usr/local/lib/python3.10/dist-packages (from jupyter-server<3,>=1.8->notebook-shim>=0.2.3->nbclassic>=0.4.7->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.8.0)
Requirement already satisfied: sniffio>=1.1 in /usr/local/lib/python3.10/dist-packages (from anyio<4,>=3.1.0->jupyter-server<3,>=1.8->notebook-shim>=0.2.3->nbclassic>=0.4.7->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.3.1)
Requirement already satisfied: exceptiongroup in /usr/local/lib/python3.10/dist-packages (from anyio<4,>=3.1.0->jupyter-server<3,>=1.8->notebook-shim>=0.2.3->nbclassic>=0.4.7->notebook>=4.4.1->widgetsnbextension~=3.6.0->ipywidgets>=7.6.5->pycaret) (1.2.1)
Building wheels for collected packages: pyod
  Building wheel for pyod (setup.py) ... [?25l[?25hdone
  Created wheel for pyod: filename=pyod-2.0.1-py3-none-any.whl size=193267 sha256=333f7491080c668f6bceaf0c2cc8f6206cf8e0eee7ca91e2ea968cbeddde6640
  Stored in directory: /root/.cache/pip/wheels/94/75/88/b853cf33b0053b0a001dca55b74d515048b7656e736364eb57
Successfully built pyod
Installing collected packages: kaleido, dash-table, dash-html-components, dash-core-components, xxhash, wurlitzer, tsdownsample, scikit-base, schemdraw, retrying, orjson, joblib, jedi, deprecation, scikit-learn, sktime, scikit-plot, pyod, imbalanced-learn, dash, pmdarima, plotly-resampler, category-encoders, tbats, pycaret
  Attempting uninstall: joblib
    Found existing installation: joblib 1.4.2
    Uninstalling joblib-1.4.2:
      Successfully uninstalled joblib-1.4.2
  Attempting uninstall: scikit-learn
    Found existing installation: scikit-learn 1.2.2
    Uninstalling scikit-learn-1.2.2:
      Successfully uninstalled scikit-learn-1.2.2
  Attempting uninstall: imbalanced-learn
    Found existing installation: imbalanced-learn 0.10.1
    Uninstalling imbalanced-learn-0.10.1:
      Successfully uninstalled imbalanced-learn-0.10.1
Successfully installed category-encoders-2.6.3 dash-2.17.1 dash-core-components-2.0.0 dash-html-components-2.0.0 dash-table-5.0.0 deprecation-2.1.0 imbalanced-learn-0.12.3 jedi-0.19.1 joblib-1.3.2 kaleido-0.2.1 orjson-3.10.5 plotly-resampler-0.10.0 pmdarima-2.0.4 pycaret-3.3.2 pyod-2.0.1 retrying-1.3.4 schemdraw-0.15 scikit-base-0.7.8 scikit-learn-1.4.2 scikit-plot-0.3.7 sktime-0.26.0 tbats-1.1.3 tsdownsample-0.1.3 wurlitzer-3.1.1 xxhash-3.4.1

## Output 43
car_ID  symboling                   CarName fueltype aspiration  \
0         1          3        alfa-romero giulia      gas        std   
1         2          3       alfa-romero stelvio      gas        std   
2         3          1  alfa-romero Quadrifoglio      gas        std   
3         4          2               audi 100 ls      gas        std   
4         5          2                audi 100ls      gas        std   
..      ...        ...                       ...      ...        ...   
200     201         -1           volvo 145e (sw)      gas        std   
201     202         -1               volvo 144ea      gas      turbo   
202     203         -1               volvo 244dl      gas        std   
203     204         -1                 volvo 246   diesel      turbo   
204     205         -1               volvo 264gl      gas      turbo   

    doornumber      carbody drivewheel enginelocation  wheelbase  ...  \
0          two  convertible        rwd          front       88.6  ...   
1          two  convertible        rwd          front       88.6  ...   
2          two    hatchback        rwd          front       94.5  ...   
3         four        sedan        fwd          front       99.8  ...   
4         four        sedan        4wd          front       99.4  ...   
..         ...          ...        ...            ...        ...  ...   
200       four        sedan        rwd          front      109.1  ...   
201       four        sedan        rwd          front      109.1  ...   
202       four        sedan        rwd          front      109.1  ...   
203       four        sedan        rwd          front      109.1  ...   
204       four        sedan        rwd          front      109.1  ...   

     enginesize  fuelsystem  boreratio  stroke compressionratio horsepower  \
0           130        mpfi       3.47    2.68              9.0        111   
1           130        mpfi       3.47    2.68              9.0        111   
2           152        mpfi       2.68    3.47              9.0        154   
3           109        mpfi       3.19    3.40             10.0        102   
4           136        mpfi       3.19    3.40              8.0        115   
..          ...         ...        ...     ...              ...        ...   
200         141        mpfi       3.78    3.15              9.5        114   
201         141        mpfi       3.78    3.15              8.7        160   
202         173        mpfi       3.58    2.87              8.8        134   
203         145         idi       3.01    3.40             23.0        106   
204         141        mpfi       3.78    3.15              9.5        114   

     peakrpm citympg  highwaympg    price  
0       5000      21          27  13495.0  
1       5000      21          27  16500.0  
2       5000      19          26  16500.0  
3       5500      24          30  13950.0  
4       5500      18          22  17450.0  
..       ...     ...         ...      ...  
200     5400      23          28  16845.0  
201     5300      19          25  19045.0  
202     5500      18          23  21485.0  
203     4800      26          27  22470.0  
204     5400      19          25  22625.0  

[205 rows x 26 columns]

## Output 44
Requirement already satisfied: torch in /usr/local/lib/python3.10/dist-packages (2.3.0+cu121)
Requirement already satisfied: filelock in /usr/local/lib/python3.10/dist-packages (from torch) (3.15.3)
Requirement already satisfied: typing-extensions>=4.8.0 in /usr/local/lib/python3.10/dist-packages (from torch) (4.12.2)
Requirement already satisfied: sympy in /usr/local/lib/python3.10/dist-packages (from torch) (1.12.1)
Requirement already satisfied: networkx in /usr/local/lib/python3.10/dist-packages (from torch) (3.3)
Requirement already satisfied: jinja2 in /usr/local/lib/python3.10/dist-packages (from torch) (3.1.4)
Requirement already satisfied: fsspec in /usr/local/lib/python3.10/dist-packages (from torch) (2023.6.0)
Collecting nvidia-cuda-nvrtc-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_nvrtc_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (23.7 MB)
Collecting nvidia-cuda-runtime-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_runtime_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (823 kB)
Collecting nvidia-cuda-cupti-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_cupti_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (14.1 MB)
Collecting nvidia-cudnn-cu12==8.9.2.26 (from torch)
  Using cached nvidia_cudnn_cu12-8.9.2.26-py3-none-manylinux1_x86_64.whl (731.7 MB)
Collecting nvidia-cublas-cu12==12.1.3.1 (from torch)
  Using cached nvidia_cublas_cu12-12.1.3.1-py3-none-manylinux1_x86_64.whl (410.6 MB)
Collecting nvidia-cufft-cu12==11.0.2.54 (from torch)
  Using cached nvidia_cufft_cu12-11.0.2.54-py3-none-manylinux1_x86_64.whl (121.6 MB)
Collecting nvidia-curand-cu12==10.3.2.106 (from torch)
  Using cached nvidia_curand_cu12-10.3.2.106-py3-none-manylinux1_x86_64.whl (56.5 MB)
Collecting nvidia-cusolver-cu12==11.4.5.107 (from torch)
  Using cached nvidia_cusolver_cu12-11.4.5.107-py3-none-manylinux1_x86_64.whl (124.2 MB)
Collecting nvidia-cusparse-cu12==12.1.0.106 (from torch)
  Using cached nvidia_cusparse_cu12-12.1.0.106-py3-none-manylinux1_x86_64.whl (196.0 MB)
Collecting nvidia-nccl-cu12==2.20.5 (from torch)
  Using cached nvidia_nccl_cu12-2.20.5-py3-none-manylinux2014_x86_64.whl (176.2 MB)
Collecting nvidia-nvtx-cu12==12.1.105 (from torch)
  Using cached nvidia_nvtx_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (99 kB)
Requirement already satisfied: triton==2.3.0 in /usr/local/lib/python3.10/dist-packages (from torch) (2.3.0)
Collecting nvidia-nvjitlink-cu12 (from nvidia-cusolver-cu12==11.4.5.107->torch)
  Downloading nvidia_nvjitlink_cu12-12.5.40-py3-none-manylinux2014_x86_64.whl (21.3 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m21.3/21.3 MB[0m [31m51.8 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.10/dist-packages (from jinja2->torch) (2.1.5)
Requirement already satisfied: mpmath<1.4.0,>=1.1.0 in /usr/local/lib/python3.10/dist-packages (from sympy->torch) (1.3.0)
Installing collected packages: nvidia-nvtx-cu12, nvidia-nvjitlink-cu12, nvidia-nccl-cu12, nvidia-curand-cu12, nvidia-cufft-cu12, nvidia-cuda-runtime-cu12, nvidia-cuda-nvrtc-cu12, nvidia-cuda-cupti-cu12, nvidia-cublas-cu12, nvidia-cusparse-cu12, nvidia-cudnn-cu12, nvidia-cusolver-cu12
Successfully installed nvidia-cublas-cu12-12.1.3.1 nvidia-cuda-cupti-cu12-12.1.105 nvidia-cuda-nvrtc-cu12-12.1.105 nvidia-cuda-runtime-cu12-12.1.105 nvidia-cudnn-cu12-8.9.2.26 nvidia-cufft-cu12-11.0.2.54 nvidia-curand-cu12-10.3.2.106 nvidia-cusolver-cu12-11.4.5.107 nvidia-cusparse-cu12-12.1.0.106 nvidia-nccl-cu12-2.20.5 nvidia-nvjitlink-cu12-12.5.40 nvidia-nvtx-cu12-12.1.105

## Output 45
Requirement already satisfied: torch in /usr/local/lib/python3.10/dist-packages (2.3.0+cu121)
Requirement already satisfied: transformers in /usr/local/lib/python3.10/dist-packages (4.41.2)
Requirement already satisfied: filelock in /usr/local/lib/python3.10/dist-packages (from torch) (3.15.3)
Requirement already satisfied: typing-extensions>=4.8.0 in /usr/local/lib/python3.10/dist-packages (from torch) (4.12.2)
Requirement already satisfied: sympy in /usr/local/lib/python3.10/dist-packages (from torch) (1.12.1)
Requirement already satisfied: networkx in /usr/local/lib/python3.10/dist-packages (from torch) (3.3)
Requirement already satisfied: jinja2 in /usr/local/lib/python3.10/dist-packages (from torch) (3.1.4)
Requirement already satisfied: fsspec in /usr/local/lib/python3.10/dist-packages (from torch) (2023.6.0)
Requirement already satisfied: nvidia-cuda-nvrtc-cu12==12.1.105 in /usr/local/lib/python3.10/dist-packages (from torch) (12.1.105)
Requirement already satisfied: nvidia-cuda-runtime-cu12==12.1.105 in /usr/local/lib/python3.10/dist-packages (from torch) (12.1.105)
Requirement already satisfied: nvidia-cuda-cupti-cu12==12.1.105 in /usr/local/lib/python3.10/dist-packages (from torch) (12.1.105)
Requirement already satisfied: nvidia-cudnn-cu12==8.9.2.26 in /usr/local/lib/python3.10/dist-packages (from torch) (8.9.2.26)
Requirement already satisfied: nvidia-cublas-cu12==12.1.3.1 in /usr/local/lib/python3.10/dist-packages (from torch) (12.1.3.1)
Requirement already satisfied: nvidia-cufft-cu12==11.0.2.54 in /usr/local/lib/python3.10/dist-packages (from torch) (11.0.2.54)
Requirement already satisfied: nvidia-curand-cu12==10.3.2.106 in /usr/local/lib/python3.10/dist-packages (from torch) (10.3.2.106)
Requirement already satisfied: nvidia-cusolver-cu12==11.4.5.107 in /usr/local/lib/python3.10/dist-packages (from torch) (11.4.5.107)
Requirement already satisfied: nvidia-cusparse-cu12==12.1.0.106 in /usr/local/lib/python3.10/dist-packages (from torch) (12.1.0.106)
Requirement already satisfied: nvidia-nccl-cu12==2.20.5 in /usr/local/lib/python3.10/dist-packages (from torch) (2.20.5)
Requirement already satisfied: nvidia-nvtx-cu12==12.1.105 in /usr/local/lib/python3.10/dist-packages (from torch) (12.1.105)
Requirement already satisfied: triton==2.3.0 in /usr/local/lib/python3.10/dist-packages (from torch) (2.3.0)
Requirement already satisfied: nvidia-nvjitlink-cu12 in /usr/local/lib/python3.10/dist-packages (from nvidia-cusolver-cu12==11.4.5.107->torch) (12.5.40)
Requirement already satisfied: huggingface-hub<1.0,>=0.23.0 in /usr/local/lib/python3.10/dist-packages (from transformers) (0.23.4)
Requirement already satisfied: numpy>=1.17 in /usr/local/lib/python3.10/dist-packages (from transformers) (1.25.2)
Requirement already satisfied: packaging>=20.0 in /usr/local/lib/python3.10/dist-packages (from transformers) (24.1)
Requirement already satisfied: pyyaml>=5.1 in /usr/local/lib/python3.10/dist-packages (from transformers) (6.0.1)
Requirement already satisfied: regex!=2019.12.17 in /usr/local/lib/python3.10/dist-packages (from transformers) (2024.5.15)
Requirement already satisfied: requests in /usr/local/lib/python3.10/dist-packages (from transformers) (2.31.0)
Requirement already satisfied: tokenizers<0.20,>=0.19 in /usr/local/lib/python3.10/dist-packages (from transformers) (0.19.1)
Requirement already satisfied: safetensors>=0.4.1 in /usr/local/lib/python3.10/dist-packages (from transformers) (0.4.3)
Requirement already satisfied: tqdm>=4.27 in /usr/local/lib/python3.10/dist-packages (from transformers) (4.66.4)
Requirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.10/dist-packages (from jinja2->torch) (2.1.5)
Requirement already satisfied: charset-normalizer<4,>=2 in /usr/local/lib/python3.10/dist-packages (from requests->transformers) (3.3.2)
Requirement already satisfied: idna<4,>=2.5 in /usr/local/lib/python3.10/dist-packages (from requests->transformers) (3.7)
Requirement already satisfied: urllib3<3,>=1.21.1 in /usr/local/lib/python3.10/dist-packages (from requests->transformers) (2.0.7)
Requirement already satisfied: certifi>=2017.4.17 in /usr/local/lib/python3.10/dist-packages (from requests->transformers) (2024.6.2)
Requirement already satisfied: mpmath<1.4.0,>=1.1.0 in /usr/local/lib/python3.10/dist-packages (from sympy->torch) (1.3.0)

## Output 46
Special tokens have been added in the vocabulary, make sure the associated word embeddings are fine-tuned or trained.

## Output 47
கடினமாகப் பிடிக்க

## Output 48
[nltk_data] Downloading package punkt to /root/nltk_data...
[nltk_data]   Unzipping tokenizers/punkt.zip.
[nltk_data] Downloading package stopwords to /root/nltk_data...
[nltk_data]   Unzipping corpora/stopwords.zip.

## Output 49
True

## Output 50
[[0.52547275 0.         0.         0.         0.52547275 0.41428875
  0.52547275]
 [0.         1.         0.         0.         0.         0.
  0.        ]
 [0.         0.         1.         0.         0.         0.
  0.        ]
 [0.         0.         0.         0.78528828 0.         0.6191303
  0.        ]]

## Output 51
[0 1 0 0]

## Output 52
/usr/local/lib/python3.10/dist-packages/sklearn/cluster/_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to 'auto' in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(

## Output 53
Requirement already satisfied: torch in /usr/local/lib/python3.10/dist-packages (2.3.0+cu121)
Requirement already satisfied: filelock in /usr/local/lib/python3.10/dist-packages (from torch) (3.15.4)
Requirement already satisfied: typing-extensions>=4.8.0 in /usr/local/lib/python3.10/dist-packages (from torch) (4.12.2)
Requirement already satisfied: sympy in /usr/local/lib/python3.10/dist-packages (from torch) (1.12.1)
Requirement already satisfied: networkx in /usr/local/lib/python3.10/dist-packages (from torch) (3.3)
Requirement already satisfied: jinja2 in /usr/local/lib/python3.10/dist-packages (from torch) (3.1.4)
Requirement already satisfied: fsspec in /usr/local/lib/python3.10/dist-packages (from torch) (2023.6.0)
Collecting nvidia-cuda-nvrtc-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_nvrtc_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (23.7 MB)
Collecting nvidia-cuda-runtime-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_runtime_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (823 kB)
Collecting nvidia-cuda-cupti-cu12==12.1.105 (from torch)
  Using cached nvidia_cuda_cupti_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (14.1 MB)
Collecting nvidia-cudnn-cu12==8.9.2.26 (from torch)
  Using cached nvidia_cudnn_cu12-8.9.2.26-py3-none-manylinux1_x86_64.whl (731.7 MB)
Collecting nvidia-cublas-cu12==12.1.3.1 (from torch)
  Using cached nvidia_cublas_cu12-12.1.3.1-py3-none-manylinux1_x86_64.whl (410.6 MB)
Collecting nvidia-cufft-cu12==11.0.2.54 (from torch)
  Using cached nvidia_cufft_cu12-11.0.2.54-py3-none-manylinux1_x86_64.whl (121.6 MB)
Collecting nvidia-curand-cu12==10.3.2.106 (from torch)
  Using cached nvidia_curand_cu12-10.3.2.106-py3-none-manylinux1_x86_64.whl (56.5 MB)
Collecting nvidia-cusolver-cu12==11.4.5.107 (from torch)
  Using cached nvidia_cusolver_cu12-11.4.5.107-py3-none-manylinux1_x86_64.whl (124.2 MB)
Collecting nvidia-cusparse-cu12==12.1.0.106 (from torch)
  Using cached nvidia_cusparse_cu12-12.1.0.106-py3-none-manylinux1_x86_64.whl (196.0 MB)
Collecting nvidia-nccl-cu12==2.20.5 (from torch)
  Using cached nvidia_nccl_cu12-2.20.5-py3-none-manylinux2014_x86_64.whl (176.2 MB)
Collecting nvidia-nvtx-cu12==12.1.105 (from torch)
  Using cached nvidia_nvtx_cu12-12.1.105-py3-none-manylinux1_x86_64.whl (99 kB)
Requirement already satisfied: triton==2.3.0 in /usr/local/lib/python3.10/dist-packages (from torch) (2.3.0)
Collecting nvidia-nvjitlink-cu12 (from nvidia-cusolver-cu12==11.4.5.107->torch)
  Downloading nvidia_nvjitlink_cu12-12.5.82-py3-none-manylinux2014_x86_64.whl (21.3 MB)
[2K     [90m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━[0m [32m21.3/21.3 MB[0m [31m27.4 MB/s[0m eta [36m0:00:00[0m
[?25hRequirement already satisfied: MarkupSafe>=2.0 in /usr/local/lib/python3.10/dist-packages (from jinja2->torch) (2.1.5)
Requirement already satisfied: mpmath<1.4.0,>=1.1.0 in /usr/local/lib/python3.10/dist-packages (from sympy->torch) (1.3.0)
Installing collected packages: nvidia-nvtx-cu12, nvidia-nvjitlink-cu12, nvidia-nccl-cu12, nvidia-curand-cu12, nvidia-cufft-cu12, nvidia-cuda-runtime-cu12, nvidia-cuda-nvrtc-cu12, nvidia-cuda-cupti-cu12, nvidia-cublas-cu12, nvidia-cusparse-cu12, nvidia-cudnn-cu12, nvidia-cusolver-cu12
Successfully installed nvidia-cublas-cu12-12.1.3.1 nvidia-cuda-cupti-cu12-12.1.105 nvidia-cuda-nvrtc-cu12-12.1.105 nvidia-cuda-runtime-cu12-12.1.105 nvidia-cudnn-cu12-8.9.2.26 nvidia-cufft-cu12-11.0.2.54 nvidia-curand-cu12-10.3.2.106 nvidia-cusolver-cu12-11.4.5.107 nvidia-cusparse-cu12-12.1.0.106 nvidia-nccl-cu12-2.20.5 nvidia-nvjitlink-cu12-12.5.82 nvidia-nvtx-cu12-12.1.105

## Output 54
(532898, 8)

## Output 55
Impressions       0
From Home         0
From Hashtags     0
From Explore      0
From Other        0
Saves             0
Comments          0
Shares            0
Likes             0
Profile Visits    0
Follows           0
Caption           0
Hashtags          0
dtype: int64
        Impressions     From Home  From Hashtags  From Explore   From Other  \
count    119.000000    119.000000     119.000000    119.000000   119.000000   
mean    5703.991597   2475.789916    1887.512605   1078.100840   171.092437   
std     4843.780105   1489.386348    1884.361443   2613.026132   289.431031   
min     1941.000000   1133.000000     116.000000      0.000000     9.000000   
25%     3467.000000   1945.000000     726.000000    157.500000    38.000000   
50%     4289.000000   2207.000000    1278.000000    326.000000    74.000000   
75%     6138.000000   2602.500000    2363.500000    689.500000   196.000000   
max    36919.000000  13473.000000   11817.000000  17414.000000  2547.000000   

             Saves    Comments      Shares       Likes  Profile Visits  \
count   119.000000  119.000000  119.000000  119.000000      119.000000   
mean    153.310924    6.663866    9.361345  173.781513       50.621849   
std     156.317731    3.544576   10.089205   82.378947       87.088402   
min      22.000000    0.000000    0.000000   72.000000        4.000000   
25%      65.000000    4.000000    3.000000  121.500000       15.000000   
50%     109.000000    6.000000    6.000000  151.000000       23.000000   
75%     169.000000    8.000000   13.500000  204.000000       42.000000   
max    1095.000000   19.000000   75.000000  549.000000      611.000000   

          Follows  
count  119.000000  
mean    20.756303  
std     40.921580  
min      0.000000  
25%      4.000000  
50%      8.000000  
75%     18.000000  
max    260.000000
