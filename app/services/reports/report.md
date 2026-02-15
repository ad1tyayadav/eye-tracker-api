Detected 9 unique calibration points. Setting k=9.

## Before any modifications

====================================================================================================
MODEL: Linear Regression
====================================================================================================

Model Linear Regression has no hyperparameter grid defined for GridSearchCV.

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Score X: 0.8210933512146253
Time X: 0.0
Score Y: 0.955456427962058
Time Y: 0.0008034706115722656
Pipeline Result -> Avg Accuracy: 235.3662, Avg Precision: 49.1126, Total Time: 1.56s

====================================================================================================
MODEL: Ridge Regression
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.7475 | 241.7027 | {'ridge**alpha': 0.01}
2 | 0.6979 | 273.3379 | {'ridge**alpha': 100}
3 | 0.6836 | 269.0442 | {'ridge**alpha': 55}
4 | 0.6800 | 268.6203 | {'ridge**alpha': 50}
5 | 0.6757 | 268.2162 | {'ridge\_\_alpha': 45}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 0.2734954357147217
Time Y: 0.2774362564086914
Pipeline Result -> Avg Accuracy: 236.1323, Avg Precision: 48.8059, Total Time: 0.66s

====================================================================================================
MODEL: Lasso Regression
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.6749 | 289.7889 | {'lasso**alpha': 100}
2 | 0.6694 | 275.8380 | {'lasso**alpha': 55}
3 | 0.6678 | 274.6908 | {'lasso**alpha': 50}
4 | 0.6658 | 273.6146 | {'lasso**alpha': 45}
5 | 0.6634 | 272.5937 | {'lasso\_\_alpha': 40}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 0.3323993682861328
Time Y: 0.31626462936401367
Pipeline Result -> Avg Accuracy: 290.8152, Avg Precision: 45.8779, Total Time: 0.77s

====================================================================================================
MODEL: Elastic Net
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.6996 | 274.9757 | {'elasticnet**alpha': 1.0, 'elasticnet**l1_ratio': 0.8}
2 | 0.6896 | 291.7449 | {'elasticnet**alpha': 1.0, 'elasticnet**l1_ratio': 0.5}
3 | 0.6851 | 269.2697 | {'elasticnet**alpha': 0.1, 'elasticnet**l1_ratio': 0}
4 | 0.6848 | 269.2195 | {'elasticnet**alpha': 0.1, 'elasticnet**l1_ratio': 0.01}
5 | 0.6768 | 268.2999 | {'elasticnet**alpha': 0.1, 'elasticnet**l1_ratio': 0.2}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Score X: 0.7457386415719489
Time X: 0.0
Score Y: 0.9049978924542859
Time Y: 0.0
Pipeline Result -> Avg Accuracy: 298.9683, Avg Precision: 38.6566, Total Time: 0.11s

====================================================================================================
MODEL: Bayesian Ridge
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1, 'bayesianridge**lambda_init': 1e-09}
2 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.3, 'bayesianridge**lambda_init': 1e-09}
3 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.1, 'bayesianridge**lambda_init': 1e-09}
4 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.2, 'bayesianridge**lambda_init': 1e-09}
5 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.4, 'bayesianridge**lambda_init': 1e-09}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 0.801609992980957
Time Y: 0.7761216163635254
Pipeline Result -> Avg Accuracy: 235.3889, Avg Precision: 48.1209, Total Time: 1.69s

====================================================================================================
MODEL: SGD Regressor
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.7123 | 256.6649 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.7, 'sgdregressor**max_iter': 1000}
2 | 0.7123 | 256.6659 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0, 'sgdregressor**max_iter': 1000}
3 | 0.7123 | 256.6661 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.2, 'sgdregressor**max_iter': 1000}
4 | 0.7123 | 256.6659 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 1, 'sgdregressor**max_iter': 1000}
5 | 0.7123 | 256.6658 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.5, 'sgdregressor**max_iter': 1000}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 7.285875558853149
Time Y: 7.9095728397369385
Pipeline Result -> Avg Accuracy: 241.2138, Avg Precision: 46.8787, Total Time: 15.31s

====================================================================================================
MODEL: Support Vector Regressor
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.9087 | 75.2710 | {'svr**C': 1000, 'svr**gamma': 1, 'svr**kernel': 'rbf'}
2 | 0.9074 | 87.7716 | {'svr**C': 100, 'svr**gamma': 1, 'svr**kernel': 'rbf'}
3 | 0.8694 | 120.2317 | {'svr**C': 1000, 'svr**gamma': 0.1, 'svr**kernel': 'rbf'}
4 | 0.8157 | 137.6160 | {'svr**C': 100, 'svr**gamma': 0.1, 'svr**kernel': 'rbf'}
5 | 0.7947 | 167.9109 | {'svr**C': 1000, 'svr**gamma': 0.01, 'svr\_\_kernel': 'rbf'}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Score X: 0.7693369168357224
Time X: 0.0077130794525146484
Score Y: 0.9476667108830322
Time Y: 0.005934715270996094
Pipeline Result -> Avg Accuracy: 266.1792, Avg Precision: 48.0700, Total Time: 0.13s

====================================================================================================
MODEL: Random Forest Regressor
====================================================================================================

Model Random Forest Regressor has no hyperparameter grid defined for GridSearchCV.

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Pipeline Error: 'Random Forest Regressor'

================================================================================
OVERALL PERFORMANCE SUMMARY
================================================================================
Model Name | Avg Accuracy | Avg Precision | Time (s)

---

Linear Regression | 235.3662 | 49.1126 | 1.5597
Ridge Regression | 236.1323 | 48.8059 | 0.6650
Lasso Regression | 290.8152 | 45.8779 | 0.7684
Elastic Net | 298.9683 | 38.6566 | 0.1052
Bayesian Ridge | 235.3889 | 48.1209 | 1.6910
SGD Regressor | 241.2138 | 46.8787 | 15.3096
Support Vector Regressor | 266.1792 | 48.0700 | 0.1342
Random Forest Regressor | ERROR: 'Random Forest Regressor'

---

## After modification and adding randomforset configuration

Detected 9 unique calibration points. Setting k=9.

====================================================================================================
MODEL: Linear Regression
====================================================================================================

Model Linear Regression has no hyperparameter grid defined for GridSearchCV.

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Score X: 0.8210933512146253
Time X: 0.0
Score Y: 0.955456427962058
Time Y: 0.0
Pipeline Result -> Avg Accuracy: 235.3662, Avg Precision: 49.1126, Total Time: 1.50s

====================================================================================================
MODEL: Ridge Regression
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.7497 | 241.3809 | {'ridge**alpha': 0.005}
2 | 0.7475 | 241.7027 | {'ridge**alpha': 0.01}
3 | 0.7118 | 268.2630 | {'ridge**alpha': 100}
4 | 0.6966 | 263.7161 | {'ridge**alpha': 50}
5 | 0.6468 | 261.6515 | {'ridge\_\_alpha': 20}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 0.14182019233703613
Time Y: 0.1409766674041748
Pipeline Result -> Avg Accuracy: 235.8727, Avg Precision: 48.7106, Total Time: 0.39s

====================================================================================================
MODEL: Lasso Regression
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.6749 | 289.7889 | {'lasso**alpha': 100}
2 | 0.6694 | 275.8380 | {'lasso**alpha': 55}
3 | 0.6678 | 274.6908 | {'lasso**alpha': 50}
4 | 0.6658 | 273.6146 | {'lasso**alpha': 45}
5 | 0.6634 | 272.5937 | {'lasso\_\_alpha': 40}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 0.15945863723754883
Time Y: 0.15405631065368652
Pipeline Result -> Avg Accuracy: 292.7949, Avg Precision: 45.1035, Total Time: 0.41s

====================================================================================================
MODEL: Elastic Net
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.7005 | 277.8284 | {'elasticnet**alpha': 0.5, 'elasticnet**l1_ratio': 0.5}
2 | 0.6999 | 280.8068 | {'elasticnet**alpha': 1.0, 'elasticnet**l1_ratio': 0.7}
3 | 0.6998 | 275.1441 | {'elasticnet**alpha': 2.0, 'elasticnet**l1_ratio': 0.9}
4 | 0.6996 | 274.9757 | {'elasticnet**alpha': 1.0, 'elasticnet**l1_ratio': 0.8}
5 | 0.6957 | 286.5466 | {'elasticnet**alpha': 2.0, 'elasticnet**l1_ratio': 0.8}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Score X: 0.7457386415719489
Time X: 0.0
Score Y: 0.9049978924542859
Time Y: 0.0
Pipeline Result -> Avg Accuracy: 298.9683, Avg Precision: 38.6566, Total Time: 0.13s

====================================================================================================
MODEL: Bayesian Ridge
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1, 'bayesianridge**lambda_init': 1e-09}
2 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.3, 'bayesianridge**lambda_init': 1e-09}
3 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.1, 'bayesianridge**lambda_init': 1e-09}
4 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.2, 'bayesianridge**lambda_init': 1e-09}
5 | 0.2365 | 255.4301 | {'bayesianridge**alpha_init': 1.4, 'bayesianridge**lambda_init': 1e-09}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 0.7946014404296875
Time Y: 0.7750468254089355
Pipeline Result -> Avg Accuracy: 235.3889, Avg Precision: 48.1209, Total Time: 1.68s

====================================================================================================
MODEL: SGD Regressor
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.7123 | 256.6659 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.8, 'sgdregressor**max_iter': 1000}
2 | 0.7123 | 256.6640 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 1, 'sgdregressor**max_iter': 1000}
3 | 0.7123 | 256.6659 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.7, 'sgdregressor**max_iter': 1000}
4 | 0.7123 | 256.6657 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.5, 'sgdregressor**max_iter': 1000}
5 | 0.7123 | 256.7432 | {'sgdregressor**alpha': 0.001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.8, 'sgdregressor**max_iter': 1000}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 1.793349027633667
Time Y: 1.8706464767456055
Pipeline Result -> Avg Accuracy: 241.2358, Avg Precision: 46.9392, Total Time: 3.78s

====================================================================================================
MODEL: Support Vector Regressor
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.9167 | 68.5502 | {'svr**C': 1000, 'svr**gamma': 2, 'svr**kernel': 'rbf'}
2 | 0.9162 | 69.3407 | {'svr**C': 500, 'svr**gamma': 2, 'svr**kernel': 'rbf'}
3 | 0.9149 | 68.6453 | {'svr**C': 2000, 'svr**gamma': 2, 'svr**kernel': 'rbf'}
4 | 0.9144 | 68.0756 | {'svr**C': 500, 'svr**gamma': 5, 'svr**kernel': 'rbf'}
5 | 0.9132 | 72.2102 | {'svr**C': 200, 'svr**gamma': 2, 'svr\_\_kernel': 'rbf'}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Score X: 0.7693369168357224
Time X: 0.0162813663482666
Score Y: 0.9476667108830322
Time Y: 0.019759178161621094
Pipeline Result -> Avg Accuracy: 266.1792, Avg Precision: 48.0700, Total Time: 0.36s

====================================================================================================
MODEL: Random Forest Regressor
====================================================================================================

Searching for top 5 parameter combinations (Axis X)...
Rank | R2 Score | MAE | Parameters

---

1 | 0.9221 | 68.1083 | {'randomforestregressor**max_depth': 10, 'randomforestregressor**min_samples_split': 10, 'randomforestregressor**n_estimators': 100}
2 | 0.9180 | 68.5070 | {'randomforestregressor**max_depth': 10, 'randomforestregressor**min_samples_split': 5, 'randomforestregressor**n_estimators': 100}
3 | 0.9147 | 69.0029 | {'randomforestregressor**max_depth': 10, 'randomforestregressor**min_samples_split': 2, 'randomforestregressor\_\_n_estimators': 100}

Running full 'predict' pipeline...
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 751.846863 270.624054 641.400879 275.499695 100.0 100.0
1 739.366943 275.130646 641.746643 276.419403 100.0 100.0
2 739.202148 273.828247 641.387695 275.756897 100.0 100.0
3 739.340332 273.977570 641.849548 276.237335 100.0 100.0
4 738.536682 274.158722 641.225525 276.203308 100.0 100.0
Time X: 3.1839962005615234
Time Y: 1.0933246612548828
Pipeline Result -> Avg Accuracy: 52.8510, Avg Precision: 31.9563, Total Time: 4.43s

================================================================================
OVERALL PERFORMANCE SUMMARY
================================================================================
Model Name | Avg Accuracy | Avg Precision | Time (s)

---

Linear Regression | 235.3662 | 49.1126 | 1.4983
Ridge Regression | 235.8727 | 48.7106 | 0.3908
Lasso Regression | 292.7949 | 45.1035 | 0.4128
Elastic Net | 298.9683 | 38.6566 | 0.1328
Bayesian Ridge | 235.3889 | 48.1209 | 1.6843
SGD Regressor | 241.2358 | 46.9392 | 3.7777
Support Vector Regressor | 266.1792 | 48.0700 | 0.3644
Random Forest Regressor | 52.8510 | 31.9563 | 4.4307

---

## After spliting to test and train to check if there any overfitting

Full Dataset: 900 rows
Training Split: 765 rows
Validation Split: 135 rows
Detected 9 unique calibration points.

====================================================================================================
MODEL: Linear Regression
====================================================================================================

Model Linear Regression has no hyperparameter grid defined.

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Score X: 0.07148328938658532
Time X: 0.002007007598876953
Score Y: 0.9278236134235549
Time Y: 0.0018939971923828125
Calibration Result -> Acc: 245.7273, Prec: 49.8420, Time: 1.55s

--- Phase 2: Validation Phase (Hold-out Split) ---
Score X_Val: 0.8200780206843142
Time X_Val: 0.0019996166229248047
Score Y_Val: 0.9612407162914263
Time Y_Val: 0.0010020732879638672
Validation Result -> Acc: 229.4535, Prec: 51.5457

====================================================================================================
MODEL: Ridge Regression
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.7256 | 241.3973 | {'ridge**alpha': 0.001}
2 | 0.7118 | 268.2630 | {'ridge**alpha': 100}
3 | 0.6966 | 263.7161 | {'ridge**alpha': 50}
4 | 0.6507 | 244.4687 | {'ridge**alpha': 0.005}
5 | 0.6468 | 261.6515 | {'ridge\_\_alpha': 20}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Time X: 0.15825796127319336
Time Y: 0.15566420555114746
Calibration Result -> Acc: 247.0915, Prec: 49.9354, Time: 0.42s

--- Phase 2: Validation Phase (Hold-out Split) ---
Time X_Val: 0.16522979736328125
Time Y_Val: 0.15460491180419922
Validation Result -> Acc: 229.6377, Prec: 51.8048

====================================================================================================
MODEL: Lasso Regression
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.6910 | 270.3284 | {'lasso**alpha': 55}
2 | 0.6905 | 269.0582 | {'lasso**alpha': 50}
3 | 0.6895 | 267.8433 | {'lasso**alpha': 45}
4 | 0.6881 | 266.7249 | {'lasso**alpha': 40}
5 | 0.6841 | 264.7345 | {'lasso\_\_alpha': 30}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Time X: 0.16257333755493164
Time Y: 0.16847848892211914
Calibration Result -> Acc: 251.6126, Prec: 47.0489, Time: 0.44s

--- Phase 2: Validation Phase (Hold-out Split) ---
Time X_Val: 0.18091559410095215
Time Y_Val: 0.16357016563415527
Validation Result -> Acc: 265.0815, Prec: 44.3168

====================================================================================================
MODEL: Elastic Net
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.7136 | 273.3473 | {'elasticnet**alpha': 0.5, 'elasticnet**l1_ratio': 0.5}
2 | 0.7136 | 270.6703 | {'elasticnet**alpha': 2.0, 'elasticnet**l1_ratio': 0.9}
3 | 0.7135 | 270.5027 | {'elasticnet**alpha': 1.0, 'elasticnet**l1_ratio': 0.8}
4 | 0.7123 | 276.3342 | {'elasticnet**alpha': 1.0, 'elasticnet**l1_ratio': 0.7}
5 | 0.7108 | 267.5358 | {'elasticnet**alpha': 0.5, 'elasticnet**l1_ratio': 0.7}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Score X: 0.6531754054868382
Time X: 0.0006241798400878906
Score Y: 0.9074449357286609
Time Y: 0.0008966922760009766
Calibration Result -> Acc: 301.3013, Prec: 41.3590, Time: 0.09s

--- Phase 2: Validation Phase (Hold-out Split) ---
Score X_Val: 0.7340912725347744
Time X_Val: 0.0018773078918457031
Score Y_Val: 0.9125809129793833
Time Y_Val: 0.0009999275207519531
Validation Result -> Acc: 294.6057, Prec: 38.2533

====================================================================================================
MODEL: Bayesian Ridge
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.3463 | 251.4715 | {'bayesianridge**alpha_init': 1, 'bayesianridge**lambda_init': 0.001}
2 | 0.3463 | 251.4715 | {'bayesianridge**alpha_init': 1.1, 'bayesianridge**lambda_init': 0.001}
3 | 0.3463 | 251.4715 | {'bayesianridge**alpha_init': 1.2, 'bayesianridge**lambda_init': 0.001}
4 | 0.3463 | 251.4715 | {'bayesianridge**alpha_init': 1.3, 'bayesianridge**lambda_init': 0.001}
5 | 0.3463 | 251.4715 | {'bayesianridge**alpha_init': 1.4, 'bayesianridge**lambda_init': 0.001}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Time X: 0.7953126430511475
Time Y: 0.79813551902771
Calibration Result -> Acc: 246.8617, Prec: 50.2630, Time: 1.69s

--- Phase 2: Validation Phase (Hold-out Split) ---
Time X_Val: 0.8207540512084961
Time Y_Val: 0.8074281215667725
Validation Result -> Acc: 229.1080, Prec: 50.9408

====================================================================================================
MODEL: SGD Regressor
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.7240 | 252.4349 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.8, 'sgdregressor**max_iter': 1000}
2 | 0.7240 | 252.4352 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 1, 'sgdregressor**max_iter': 1000}
3 | 0.7240 | 252.4355 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.5, 'sgdregressor**max_iter': 1000}
4 | 0.7240 | 252.4360 | {'sgdregressor**alpha': 0.0001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.7, 'sgdregressor**max_iter': 1000}
5 | 0.7239 | 252.5118 | {'sgdregressor**alpha': 0.001, 'sgdregressor**eta0': 0.0001, 'sgdregressor**l1_ratio': 0.5, 'sgdregressor**max_iter': 1000}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Time X: 1.9512312412261963
Time Y: 1.9312074184417725
Calibration Result -> Acc: 247.0398, Prec: 49.5953, Time: 3.98s

--- Phase 2: Validation Phase (Hold-out Split) ---
Time X_Val: 1.7748675346374512
Time Y_Val: 1.8547911643981934
Validation Result -> Acc: 239.2565, Prec: 48.5600

====================================================================================================
MODEL: Support Vector Regressor
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.9196 | 63.4319 | {'svr**C': 1000, 'svr**gamma': 5, 'svr**kernel': 'rbf'}
2 | 0.9191 | 66.7000 | {'svr**C': 1000, 'svr**gamma': 2, 'svr**kernel': 'rbf'}
3 | 0.9186 | 67.8033 | {'svr**C': 500, 'svr**gamma': 2, 'svr**kernel': 'rbf'}
4 | 0.9181 | 65.6786 | {'svr**C': 500, 'svr**gamma': 5, 'svr**kernel': 'rbf'}
5 | 0.9180 | 66.6653 | {'svr**C': 2000, 'svr**gamma': 2, 'svr\_\_kernel': 'rbf'}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Score X: 0.6935454371850305
Time X: 0.018875598907470703
Score Y: 0.9363413011174913
Time Y: 0.011532068252563477
Calibration Result -> Acc: 281.0235, Prec: 49.7874, Time: 0.22s

--- Phase 2: Validation Phase (Hold-out Split) ---
Score X_Val: 0.7649424330422514
Time X_Val: 0.013813972473144531
Score Y_Val: 0.9553053450112502
Time Y_Val: 0.016499757766723633
Validation Result -> Acc: 257.4740, Prec: 47.0542

====================================================================================================
MODEL: Random Forest Regressor
====================================================================================================

Searching for top 5 parameter combinations...
Rank | R2 (X) | MAE (X) | Parameters

---

1 | 0.9229 | 65.8699 | {'randomforestregressor**max_depth': 10, 'randomforestregressor**min_samples_split': 10, 'randomforestregressor**n_estimators': 100}
2 | 0.9183 | 66.9455 | {'randomforestregressor**max_depth': 10, 'randomforestregressor**min_samples_split': 5, 'randomforestregressor**n_estimators': 100}
3 | 0.9137 | 67.7311 | {'randomforestregressor**max_depth': 10, 'randomforestregressor**min_samples_split': 2, 'randomforestregressor\_\_n_estimators': 100}

--- Phase 1: Calibration Phase (Internal split on Training set) ---
left_iris_x left_iris_y right_iris_x right_iris_y point_x point_y
0 725.386353 275.860901 627.103882 274.170715 1607.0 100.0
1 735.130432 282.739563 636.170105 280.775909 100.0 769.0
2 729.180908 284.334076 630.414978 282.022430 1607.0 769.0
3 730.777405 280.959167 632.483826 277.992859 853.5 434.5
4 723.184448 275.512177 625.264465 274.214630 1607.0 100.0
Time X: 3.5348854064941406
Time Y: 2.837346315383911
Calibration Result -> Acc: 69.4965, Prec: 46.4941, Time: 6.57s

--- Phase 2: Validation Phase (Hold-out Split) ---
Time X_Val: 3.585437297821045
Time Y_Val: 3.094998598098755
Validation Result -> Acc: 46.6466, Prec: 29.1507

==============================================================================================================
CONSOLIDATED TRAIN/VAL PERFORMANCE SUMMARY
==============================================================================================================
Model Name | Calib Acc | Calib Prec | Valid Acc | Valid Prec | Time (s)

---

Linear Regression | 245.7273 | 49.8420 | 229.4535 | 51.5457 | 1.5465
Ridge Regression | 247.0915 | 49.9354 | 229.6377 | 51.8048 | 0.4171
Lasso Regression | 251.6126 | 47.0489 | 265.0815 | 44.3168 | 0.4428
Elastic Net | 301.3013 | 41.3590 | 294.6057 | 38.2533 | 0.0876
Bayesian Ridge | 246.8617 | 50.2630 | 229.1080 | 50.9408 | 1.6934
SGD Regressor | 247.0398 | 49.5953 | 239.2565 | 48.5600 | 3.9767
Support Vector Regressor | 281.0235 | 49.7874 | 257.4740 | 47.0542 | 0.2224
Random Forest Regressor | 69.4965 | 46.4941 | 46.6466 | 29.1507 | 6.5670

---
