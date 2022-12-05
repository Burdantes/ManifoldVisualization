# Manifold Visualizer

## Setup and run
1. Install flask - `pip install flask`
2. Install python packages - `pip install seaborn tqdm numpy matplotlib gunicorn networkx cvxpy`  
  a. cvxpy  
  b. networkx  
  c. gunicorn  
  d. matplotlib  
  e. numpy  
  f. tqdm  
  g. seaborn   
3. Run `flask run` in the project source folder
4. Go to http://localhost:5000/

## Usage 
1. Upload a csv file with the following format:  
  a. `source, target, weight`  
  b. `source` and `target` are node names  
  c. `weight` is the edge weight
2. Click `Visualize` to see the visualization
3. Click `Download` to download the visualization as a png file 