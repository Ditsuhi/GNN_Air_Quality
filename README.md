# Graph neural network for air quality prediction: a case study in Madrid

Air quality monitoring, modelling and forecasting are considered pressing and challenging topics for citizens and decision-makers, including the government. The tools used to achieve the above goals vary depending on the opportunities provided by technological development. Much attention is currently being paid to machine learning and deep learning methods, which, compared to domain knowledge methods, often perform better in terms of collecting multidimensional information. The technique introduced in this ongoing work is an Attention Temporal Graph Convolutional Network based on a combination of attention, gated recurrent unit and graph convolution network. The proposed method was tested using air quality, meteorological and traffic data obtained from the city of Madrid for the periods January-June 2019 and January-June 2020. The evaluation metrics, including Root Mean Square Error, Mean Absolute Error and Pearson Correlation Coefficient, confirmed the proposed model's advantages compared with Long Short-Term Memory and Gated Recurrent Unit (reference models). Particularly, in terms of Root Mean Square Error, it (16.34 $μg/m^3$) outperforms Long Short-Term Memory (18.77 $μg/m^3$) by 12.95\% and GRU (19.11 $μg/m^3$) by 14.5%; in terms of Mean Absolute Error, it (13.25 $μg/m^3$) also outperforms Long Short-Term Memory (13.77 $μg/m^3$) by 3.78% and Gated Recurrent Unit (13.44 $μg/m^3$) by 1.41\%; and in terms of the Pearson Correlation Coefficient, it (0.72) outperforms Long Short-Term Memory and Gated Recurrent Unit by 5.56%.


The purpose of each file included in this repository is briefly described below:

- _GNN_NO2.ipynb_ includes steps for predicting nitrogen dioxide by implementing A3T-GCN and comparing it with the results from reference methods (LSTM and GRU).
- _Graph_Network.ipynb_ contains the procedure for constructing graph network of the air quality stations placed in the city of Madrid.
- _distanceNodes.txt_ includes the distance between the air quality stations placed in the city of Madrid (24 stations, 276 edges each edge is placed 2 times depending on the node order: origin, destination).

The final version of the preprocessed dataset can be found at the following link: https://doi.org/10.5281/zenodo.6542247.


