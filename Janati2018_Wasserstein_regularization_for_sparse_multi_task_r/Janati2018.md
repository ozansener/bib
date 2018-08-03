- In Multi-Task Feature Learning people solves 1-norm ( rmse over task for each indice): $\sum_i \sqrt{\sum_t \theta^t_i^2}$ But this requires exact shared support, one idea is using l1 norm of non-shared and this l2-l1 norm of shared.
- Basic idea is replacing the l2-l1 with OT distance since it does not required shared support. Rest is using generalized OT since parameters are not probability dist (not sum to 1). It also uses some nice optimization procedure. Only handles linear models.