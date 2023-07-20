# ITCS-6114 Project One
David Vences

## BACKGROUND
In  this project I implemented some comparison-based sorting algorithms and observed performance for different input sizes.

The sorting algorithms implemented for this project are:
- Insertion sort
- Merge sort
- Heapsort
- In-place quicksort
- Modified quicksort

## Project Requirements:

These algorithms were ran for different input sizes (e.g. 
 = 1000, 2000, 3000, 5000, 10,000 .. 40,000, 50000, 60000). Input numbers were randomly generated for the input array. Execution time was recorded and plotted on a single graph against various input sizes. The algorithms were analyzed for performance using numbers in random order, sorted order, and reverse sorted order. 

 ## Implementation
The projectOne folder contains the following:
- Jupyter notebook (AlgorithmAnalysis)
- Input used: randomOrder data and reverseOrder data
- Output: sorted data
- Report

The jupyter notebook contains the code for random data generator, the algorithms, performance timing, and plotting of the results. 


## Instructions
To repeat results simply run all the cells in the Jupyter notebook. This will create the random data, run the algorithms for three data orders, and show the plotted results. As expected, Insertion Sort performs poorly for very large data sets so running this notebook may take some time. 
