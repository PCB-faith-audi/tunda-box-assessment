city
'Nairobi'     2
'Mombasa'     2
'Kisumu'      2
'nairobi'     1
'Nairobi '    1
'Nakuru'      1
'Eldoret'     1
Name: count, dtype: int64
   order_id  customer_id  order_date     status  amount_kes payment_method
5      1006          105  2026-07-02  completed      1500.0         M-Pesa
6      1006          105  2026-07-02  completed      1500.0         M-Pesa
1
order_id          0
customer_id       0
order_date        0
status            0
amount_kes        1
payment_method    0
dtype: int64
    order_id  customer_id  order_date     status  amount_kes payment_method
20      1020          999  2026-09-26  completed      1900.0         M-Pesa
city
'Nairobi'     2
'Mombasa'     2
'Kisumu'      2
'nairobi'     1
'Nairobi '    1
'Nakuru'      1
'Eldoret'     1
Name: count, dtype: int64
count        20.000000
mean      11465.000000
std       40849.750692
min        1500.000000
25%        1887.500000
50%        2375.000000
75%        2825.000000
max      185000.000000
Name: amount_kes, dtype: float64
    order_id  customer_id  order_date     status  amount_kes payment_method
13      1013          104  2026-08-15  completed    185000.0         M-Pesa
16      1016          106  2026-09-03  completed      3300.0           Card
2       1003          103  2026-06-11  cancelled      3200.0           Card
   order_id  customer_id  order_date     status  amount_kes payment_method  \
2      1003          103  2026-06-11  cancelled      3200.0           Card   

      city signup_date      channel  
2  Mombasa  2026-06-20  Paid Social  
status
completed    17
cancelled     2
refunded      2
Name: count, dtype: int64
20
city
Nairobi    4
Mombasa    2
Kisumu     2
Nakuru     1
Eldoret    1
Name: count, dtype: int64
is_orphan         1
amount_missing    1
amount_outlier    1
dtype: int64
              name
0           orders
1        customers
2  customers_clean
3     orders_clean
      city  orders  revenue_kes
0   Kisumu       2     187100.0
1  Nairobi       9      20650.0
2  Mombasa       3       5150.0
3   Nakuru       1       3300.0
4  Unknown       1       1900.0
      city  orders  revenue_kes
0  Nairobi       9      20650.0
1  Mombasa       3       5150.0
2   Nakuru       1       3300.0
3   Kisumu       1       2100.0
4  Unknown       1       1900.0
   customer_id     city signup_date      channel
0          109  Eldoret  2026-06-21      Organic
1          110   Kisumu  2026-07-05  Paid Social
   customer_id  completed_orders
0          101                 4
1          102                 3
2          103                 1
3          104                 2
4          105                 1
5          106                 1
6          107                 2
7          108                 1
8          109                 0
9          110                 0
   all_customers  buyers  repeat_buyers  repeat_rate_of_buyers  \
0             10       8              4                   50.0   

   repeat_rate_of_all  
0                40.0  
     month  revenue_kes  prev_month  pct_change
0  2026-06       9000.0         NaN         NaN
1  2026-07       6800.0      9000.0       -24.4
2  2026-08     192000.0      6800.0      2723.5
3  2026-09      10300.0    192000.0       -94.6
     month  revenue_kes  prev_month  pct_change
0  2026-06       9000.0         NaN         NaN
1  2026-07       6800.0      9000.0       -24.4
2  2026-08       7000.0      6800.0         2.9
3  2026-09      10300.0      7000.0        47.1
14540.0 2400.0
2364.285714285714 2375.0
0.98 0.327
-0.00997854449152891 0.0299785444915289
       channel  sep_cr  oct_cr  sep_share  oct_share
0      Organic    0.06   0.061        0.8     0.5588
1  Paid Social    0.02   0.021        0.2     0.4412
0.052 0.0434 0.053
