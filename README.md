# Federated Ensemble-Learning for Transport Mode Detection in Vehicular Edge Network

Abstract: Transport Mode detection has become a crucial part of Intelligent Transportation Systems (ITS)
and Traffic Systems and management due to the recent advancements in Artificial Intelligent and
the Internet of Things (IoT). Before smartphones and smartwatches were powerful, predicting the
transportation mode of a person was difficult. Due to smart devices’ many sensors, the global cloud
servers can collect sensory data and predict a person’s commute route using several machine learning
models. Vehicular Edge Networks (VEN) connect all smart and vehicular edge devices. However,
since the data are shared globally, security is questioned, hence a large section of the population is
still unwilling to share their sensory data with the global cloud servers. Federated Learning (FL) in
VEN, a distributed technique, trains the model using a large amount of decentralized data addressing
data privacy and latency. Federated Ensemble-Learning (FedEL), a novel hybrid technique, improves
federated strategies. The federated model also uses a majority voting ensembling method to determine
users’ transportation modes. XGBoost, Random Forest, and MLP are trained with data from each
local client through an ensemble method. A prediction is then maintained based on a majority vote
among the three models. The most-voted class is considered. Based on extensive testing, the FedEL
technique has 94-95% accuracy for the 5-second window dataset and 98-99% accuracy for the half-
second window dataset on the TMD dataset.
