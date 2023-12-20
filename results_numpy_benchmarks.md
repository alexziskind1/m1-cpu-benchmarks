# Results for numpy_benchmarks.py

## M1 MacBook Air (8GB RAM, GPU Cores:7)

### numpy_benchmarks.py (conda)
=======
| datagen | 0.441 |
| special | 0.482 |
| stats | 1.264 |
| matmul | 0.833 |
| vecmul | 0.018 |
| svd | 0.701 |
| cholesky | 0.099 |
| eigendecomp | 6.177 |

### numpy_benchmarks.py (accelerate)
=======
| datagen | 0.381 |
| special | 0.447 |
| stats | 0.97 |
| matmul | 0.598 |
| vecmul | 0.01 |
| svd | 0.475 |
| cholesky | 0.074 |
| eigendecomp | 5.737 |


## M1 Max MacBook Pro (32GB RAM, GPU Cores:32) (from tlkh)

### numpy_benchmarks.py (conda)
=======
| datagen | 0.385 |
| special | 0.459 |
| stats | 1.253 |
| matmul | 0.602 |
| vecmul | 0.015 |
| svd | 1.591 |
| cholesky | 0.097 |
| eigendecomp | 7.635 |

### numpy_benchmarks.py (accelerate)
=======
| datagen | 0.348 |
| special | 0.447 |
| stats | 1.017 |
| matmul | 0.301 |
| vecmul | 0.011 |
| svd | 0.469 |
| cholesky | 0.069 |
| eigendecomp | 4.911 |


## M2 Max MacBook Pro (64GB RAM, GPU Cores:38)

### numpy_benchmarks.py (conda)
=======
| datagen | 0.365 |
| special | 0.436 |
| stats | 1.136 |
| matmul | 0.686 |
| vecmul | 0.021 |
| svd | 0.828 |
| cholesky | 0.088 |
| eigendecomp | 5.572 |

### numpy_benchmarks.py (accelerate)
=======
| datagen | 0.314 |
| special | 0.413 |
| stats | 0.705 |
| matmul | 0.253 |
| vecmul | 0.013 |
| svd | 0.299 |
| cholesky | 0.085 |
| eigendecomp | 4.267 |


## M3 Max MacBook Pro (64GB RAM, GPU Cores:40)

### numpy_benchmarks.py (conda)
=======
| datagen | 0.301 |
| special | 0.353 |
| stats | 0.765 |
| matmul | 0.394 |
| vecmul | 0.013 |
| svd | 0.406 |
| cholesky | 0.058 |
| eigendecomp | 3.548 |

### numpy_benchmarks.py (accelerate)
=======
| datagen | 0.266 |
| special | 0.323 |
| stats | 0.529 |
| matmul | 0.2 |
| vecmul | 0.007 |
| svd | 0.258 |
| cholesky | 0.059 |
| eigendecomp | 3.682 |