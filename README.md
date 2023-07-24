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

Paper Link: https://doi.org/10.1016/j.future.2023.07.022

Please cite our paper if it helps in your research.

Citation: 
```
@article{ALAM2023,
title = {Federated Ensemble-Learning for Transport Mode Detection in Vehicular Edge Network},
journal = {Future Generation Computer Systems},
year = {2023},
issn = {0167-739X},
doi = {https://doi.org/10.1016/j.future.2023.07.022},
url = {https://www.sciencedirect.com/science/article/pii/S0167739X23002674},
author = {Md. Mustakin Alam and Tanjim Ahmed and Meraz Hossain and Mehedi Hasan Emo and Md. Kausar Islam Bidhan and Md. Tanzim Reza and Md. Golam Rabiul Alam and Mohammad Mehedi Hassan and Francesco Pupo and Giancarlo Fortino},
keywords = {Transport Mode Detection, Intelligent Transportation System, Vehicular Edge Network, Federated Learning, Distributed, Majority voting},
abstract = {Transport Mode Detection (TMD) has become a crucial part of Intelligent Transportation Systems (ITS) thanks to the recent advancements in Artificial Intelligence and the Internet of Things, which enable the collection and processing of a vast amount of information on how people move and behave over space and time. Since smartphones and smartwatches have enabled people to stay connected to the internet all the time, predicting a person’s mode of transportation has become easier since live location data can be collected easily. Vehicular Edge Networks (VEN) connect all smart vehicular edge devices and global cloud servers collect those devices’ sensory data to try to predict a person’s commute route using Machine Learning models. However, since the data is shared globally, security can be compromised, causing a large section of the population to be unwilling to share their sensory data with global cloud servers. The current state-of-the-art methods have achieved high accuracy in identifying a person’s transportation mode. Nevertheless, most of the approaches do not address the privacy issues of the user data as the methods use centralized training systems. There are also decentralized federated learning systems that address the privacy issues of user data by often sacrificing the performance of the models by training them on a vast amount of decentralized data. In this research, we propose a hybrid Federated Ensemble-Learning (FedEL) model to detect transportation modes in VEN, which improves federated strategies in terms of performance as well. XGBoost, Random Forest, and MLP are trained with data from each local client through an ensemble method. A prediction is then delivered based on a majority vote among the three models, and the most-voted class is considered. Based on extensive testing, the FedEL technique delivers a 95.10% accuracy rate for a first dataset (5-second window) and a 98.61% accuracy rate for another dataset (half-second window) on a TMD dataset available in the literature.}
}
```
