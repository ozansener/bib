Basic idea is using the same function values multiple times in a single iteration via importance sampling. The key idea is:
$ f(\theta^{t_k} + \epsilon) = f(\theta^t + (\theta^{t_k} - \theta^t + \epsilon)$
Hence,
$E[f(\theta^{t_k} + \epsilon) \epsilon] =E[f(\theta^t + (\theta^{t_k} - \theta^t + \epsilon)) (\theta^{t_k} - \theta^t + \epsilon) \frac{p((\theta^{t_k} - \theta^t + \epsilon)}{p(\epsilon)} ] $
