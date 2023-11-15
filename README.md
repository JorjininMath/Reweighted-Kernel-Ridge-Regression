This repo contains the code and results for the RW-KRR with noise variance weight.

# Code Structure

# Numerical results
* Simple case
    * When compute slope, use MSE instead of RMSE
    * Use smaller dimension for Dejong (d = 3), higher dimension for Griewank (d = 10)

* Strict case with different combinations of $m$ and $n$
    * ~~Extend the range of total budgets (make minimum value smaller)~~
    * ~~Try constant noise variance to compare with benchmark paper~~
    
* Check the code is correct or not
    * Use the same settings in the reference paper and see the magnitude of RMSE
