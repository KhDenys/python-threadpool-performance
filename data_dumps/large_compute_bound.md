# Large job pool, CPU-bound

## eventlet_green_pool

|   jobs |       time |   leaked blocks |
|-------:|-----------:|----------------:|
|      0 | 0.00145388 |             726 |
|   3276 | 0.064024   |             -31 |
|   6552 | 0.136072   |               1 |
|   9828 | 0.193039   |               1 |
|  13104 | 0.258077   |               1 |
|  16380 | 0.335057   |               1 |
|  19656 | 0.396439   |               1 |
|  22932 | 0.463216   |               1 |
|  26208 | 0.526087   |               1 |
|  29484 | 0.561392   |               1 |
|  32760 | 0.615521   |               1 |
|  36036 | 0.717968   |               1 |
|  39312 | 0.755799   |               1 |
|  42588 | 0.807149   |               1 |
|  45864 | 0.868068   |               1 |
|  49140 | 0.919468   |               1 |
|  52416 | 1.00061    |               1 |
|  55692 | 1.0575     |               2 |
|  58968 | 1.09724    |               1 |
|  62244 | 1.17298    |               1 |
|  65520 | 1.2557     |               1 |


## gevent_green_pool

|   jobs |        time |   leaked blocks |
|-------:|------------:|----------------:|
|      0 | 0.000554085 |             652 |
|   3276 | 0.0684931   |              16 |
|   6552 | 0.126385    |               1 |
|   9828 | 0.192437    |               1 |
|  13104 | 0.259374    |               1 |
|  16380 | 0.326192    |               1 |
|  19656 | 0.375417    |               1 |
|  22932 | 0.45239     |               1 |
|  26208 | 0.504246    |               1 |
|  29484 | 0.570279    |               1 |
|  32760 | 0.640676    |               1 |
|  36036 | 0.702906    |               1 |
|  39312 | 0.772374    |               1 |
|  42588 | 0.832138    |               1 |
|  45864 | 0.89336     |               1 |
|  49140 | 0.960143    |               1 |
|  52416 | 1.01415     |               1 |
|  55692 | 1.12846     |               1 |
|  58968 | 1.15039     |               1 |
|  62244 | 1.22999     |               1 |
|  65520 | 1.29        |               1 |


## multiprocessing_process_pool

|   jobs |        time |   leaked blocks |
|-------:|------------:|----------------:|
|      0 | 0.000102043 |            2626 |
|   3276 | 0.606107    |             490 |
|   6552 | 0.62241     |             131 |
|   9828 | 0.640689    |             105 |
|  13104 | 0.613127    |              87 |
|  16380 | 0.679454    |              87 |
|  19656 | 0.703324    |            -344 |
|  22932 | 0.626187    |              97 |
|  26208 | 0.710225    |             458 |
|  29484 | 0.691498    |             155 |
|  32760 | 0.688219    |            -308 |
|  36036 | 0.710164    |             153 |
|  39312 | 0.708642    |             408 |
|  42588 | 0.476274    |            -316 |
|  45864 | 0.746127    |             119 |
|  49140 | 0.7306      |             581 |
|  52416 | 0.747552    |             136 |
|  55692 | 0.752032    |             120 |
|  58968 | 0.740079    |             -15 |
|  62244 | 0.734977    |             119 |
|  65520 | 0.761569    |             119 |


## multiprocessing_thread_pool

|   jobs |        time |   leaked blocks |
|-------:|------------:|----------------:|
|      0 | 4.60148e-05 |            2453 |
|   3276 | 0.0059042   |             153 |
|   6552 | 0.00806999  |            2153 |
|   9828 | 0.0102701   |            3151 |
|  13104 | 0.0188091   |            6907 |
|  16380 | 0.0141361   |             360 |
|  19656 | 0.0158641   |            -691 |
|  22932 | 0.0181      |            2691 |
|  26208 | 0.0222871   |           -2034 |
|  29484 | 0.0261939   |            3096 |
|  32760 | 0.025991    |            -727 |
|  36036 | 0.026125    |            2910 |
|  39312 | 0.0316341   |           -2638 |
|  42588 | 0.029973    |             554 |
|  45864 | 0.031146    |             570 |
|  49140 | 0.0340559   |             169 |
|  52416 | 0.0405831   |           24701 |
|  55692 | 0.0410249   |          -23338 |
|  58968 | 0.0386448   |            5309 |
|  62244 | 0.0437899   |           -3244 |
|  65520 | 0.044311    |             943 |


## thread_pool_executor

|   jobs |        time |   leaked blocks |
|-------:|------------:|----------------:|
|      0 | 1.69277e-05 |               7 |
|   3276 | 0.091327    |           -4138 |
|   6552 | 0.199103    |             695 |
|   9828 | 0.590467    |             695 |
|  13104 | 0.675434    |             695 |
|  16380 | 0.740823    |             695 |
|  19656 | 0.873481    |             695 |
|  22932 | 1.15889     |             695 |
|  26208 | 1.06442     |             695 |
|  29484 | 1.43217     |             695 |
|  32760 | 1.45273     |            1417 |
|  36036 | 1.84738     |             695 |
|  39312 | 2.20123     |             695 |
|  42588 | 1.87116     |             695 |
|  45864 | 2.60651     |            1075 |
|  49140 | 2.4277      |             695 |
|  52416 | 2.56994     |             695 |
|  55692 | 3.15152     |             695 |
|  58968 | 3.21483     |             695 |
|  62244 | 2.87422     |             695 |
|  65520 | 3.55396     |             695 |
