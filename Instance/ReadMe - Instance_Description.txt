INSTANCE FILE FORMAT DESCRIPTION
-------------------------------
Each instance file contains exactly 9 lines with the following data:

1. Variance level (δ)  
2. Number of periods (m)  
3. Number of different tariff rates  
4. Number of jobs (n)  
5. Price values for different tariff rates
6. Duration intervals [b_k, b_{k+1}] for each period k ∈ M 
7. Tariff price (c_k) for each period k ∈ M 
8. Processing time (t_i) for each job i ∈ N 
9. Energy consumption rate (p_i) for each job i ∈ N

NOTES:
- M = set of periods {1,...,m}
- N = set of jobs {1,...,n}