ML Assignment 1 — NumPy Vectorised Computation
Repository
ml-assignment-1-numpy
Assignment
This repository contains my NumPy assignment focused on vectorised computation without Python loops over NumPy array elements.
The notebook covers:
- Creating and inspecting NumPy arrays
- Converting float64 arrays to float32
- Column-wise standardisation using broadcasting
- Min-max scaling along different axes
- Handling missing values using masks and np.nanmean
- Detecting and replacing outliers
- Building a full Euclidean distance matrix using broadcasting
- Finding nearest neighbours using np.argpartition
- Comparing np.bincount with a plain Python loop
- Creating sliding windows using sliding_window_view
- Reshaping arrays and reducing across axes
- Saving and loading NumPy arrays with .npy
Files
- assignment1_numpy.ipynb — completed assignment notebook
- README.md — assignment summary and timing result
Question 8 — Speed Comparison
For counting occurrences of 1,000,000 random integers:
- NumPy np.bincount time: approximately 15 ms
- Plain Python loop time: approximately 219 ms
Speed-up:
219 / 15 = 14.6×
Therefore, NumPy was approximately 14.6× faster than the plain Python loop in this run.
Timing can vary slightly depending on the machine and runtime environment.

Requirements
- Python
- NumPy
- pandas
- Jupyter Notebook / Google Colab
Submission
Repository name: ml-assignment-1-numpy
