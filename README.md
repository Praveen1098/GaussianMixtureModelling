# Color Segementation Using Gaussian Mixture Modelling and Expectation Maximization

In this project we perform color segmentation on an underwater video sequence consisting of 3 buoys of different colors using Gaussian Mixture Modelling and Expectation
Maximization (EM) algorithm.


<p align="center">
  <p align="center"><img src="/Data/Sample.PNG"></p>
</p>


## Dependencies:

- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib
- MATLAB

## Usage

- Run the Python scripts in the current directory which contains all the codes.
- For GMM estimation pertaining to individual colored buoys, run the jupyter notebooks:
  - greenEstimate.ipynb for green color segmentation
  - yellowEstimate.ipynb for yellow color segmentation
  - orangeEstimate.ipynb for orange color segmentation
- To test the modelled GMM on a test data, run the Python scripts 
  ```
  python3 greenTest.py
  ```
  
  ```
  python3 yellowTest.py
  ```
  
  ```
  python3 orangeTest.py
  ```


