# 02456_deep_learning_e21_project
Project repository for 02456 Deep Learning E21 project at Technical University of Denmark

Hand-in of project for 02456 Deep Learning by s144269 Johan Victor Flensburg (jvfl@dtu.dk)
The code has been inspired by the weekly exercise notebooks during the course as well as example code which can be found at https://github.com/praxidike97/GraphNeuralNet/blob/master/main.py

All necessary resources can be found in the Jupyter Notebook 'gcn_online_od_prediction.ipynb'.
Running it from the top will enable everything to run. Note that if the 'torch_geometric', 'torch_sparse' or 'torch_scatter' modules are not installed, it can be done by uncommenting the top cell.

During this process random synthetic data will be created which the code can be run with. This is due to the original data being confidential.
Included are also the original training, validation and test masks and original global calendar features which are not confidential.

The graph structure is saved in a pickle named 'graph_simple_2017.pkl'.