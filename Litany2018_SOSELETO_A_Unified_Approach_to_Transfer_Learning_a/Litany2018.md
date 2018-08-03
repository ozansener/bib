Basic idea is using weighted minimization similar to robustness. The main contribution is defining this as a bi-level optimization. Outer loops optimizes final layers and the weights of the data in the source dataset. Where as inner loop optimizes over targets and features.