# Benchmark Gromacs with WSL

- Gromacs Version : 2021.4
- CUDA enabled
- Spec:
  - Ryzen 7 3700X 
  - RTX 2070 SUPER
  - 32GB 2133 Mhz

# Results
Performance with 8 cores + GPU (RTX 2070 super)
| Ubuntu 20.04 Native | W10 (21H2) + Ubuntu 20.04 WSL2 | W11 + Ubuntu 20.04 WSL2 |
|:-------------------:|:------------------------------:|:-----------------------:|
|          80         |               50               |            65           |
