Slightly discriminative version of the perceptual loss. Given a collection $x_i$ and $y_i$, you solve for $d_{ij} = min_k d(x_i,x_j)/d(x_i,x_k) + epsilon w_{ij} = d_{ij}/\sum d_{ik}$
