## SQD-ITD3
### Related implementation and model of SQD-ITD3 algorithm
	The trained neural network model is integrated into the intelligent transportation system to enhance decision-making and traffic control optimization.  The framework employs parameter sharing and distributed learning to achieve scalability, improve generalization across heterogeneous traffic environments, and facilitate cooperative learning among multiple agents.  
	The network architecture comprises a first hidden layer with 256 neurons and a second hidden layer with 128 neurons, enabling hierarchical feature extraction from complex state representations.  The final output layer generates two-dimensional action values, which correspond to the system’s s control decisions, thereby supporting adaptive and coordinated transportation management.
## Use
	The experiments were conducted on the SUMO simulation platform with the following software/hardware stack: 
	Python 3.7,
	Ubuntu 18.04,
	Intel® i7-14700F (28 logical cores),
	NVIDIA GeForce RTX 4060 Ti GPU, 
	and 32 GB RAM.
## Requirements
	matplotlib==3.4.2
	networkx==2.5.1
	numpy==1.20.0
	pillow
	pandas
	pygame
	scikit-learn==0.24.2
	scipy==1.6.3
	seaborn
	lxml
	shapely==1.8.4
	omegaconf
	sumo
## Training
	Different algorithms need to be trained 3 times using three different random seeds in three traffic modes. 
	The best performing method in the hard mode will be used in the evaluation test.
