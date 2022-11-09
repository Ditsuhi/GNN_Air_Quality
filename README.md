# Graph neural network for air quality prediction: a case study in Madrid

Air quality monitoring, modelling and forecasting are considered pressing and challenging topics for citizens and decision-makers, including the government. The tools used to achieve the above goals vary depending on the opportunities provided by technological development. Much attention is currently being paid to machine learning and deep learning methods, which, compared to domain knowledge methods, often perform better in terms of capturing, computing and processing multidimensional information and complex dependencies. The technique introduced in this work is an Attention Temporal Graph Convolutional Network based on a combination of Attention, a Gated Recurrent Unit and a Graph Convolutional Network. In the framework of the current study, it is initially suggested to use the presented approach in the domain of air quality prediction. The proposed method was tested using air quality, meteorological and traffic data obtained from the city of Madrid for the periods January-June 2019 and January-June 2022. The evaluation metrics, including Root Mean Square Error, Mean Absolute Error and Pearson Correlation Coefficient, confirmed the proposed model's advantages compared with the reference models (Temporal Graph Convolutional Network, Long Short-Term Memory and Gated Recurrent Unit).


The purpose of each file included in this repository is briefly described below:

- _GNN_NO2.ipynb_ includes steps for predicting nitrogen dioxide by implementing A3T-GCN and comparing it with the results from reference methods (LSTM and GRU).
- _Graph_Network.ipynb_ contains the procedure for constructing graph network of the air quality stations placed in the city of Madrid.
- _distanceNodes.ipynb_ includes the procedure of calculating the distance between the air quality stations placed in the city of Madrid (24 stations).
- _distanceNodes.txt_ includes the distance between the air quality stations placed in the city of Madrid (24 stations, 276 edges each edge is placed 2 times depending on the node order: origin, destination).

The final version of the preprocessed dataset can be found at the following link: https://doi.org/10.5281/zenodo.6542247.


