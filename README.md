# Detection-of-DDoS-Attack

## Introduction
A distributed denial-of-service (DDoS) attack is a malicious operation that seeks to disrupt the legitimate flow of traffic to a server, service, or network by flooding it with overwhelming network traffic.This has been a great challenge due to frequently changing attack patterns, the rapid development of cyber offense tools, and the open availability of cyber offense materials in the dark web. DDoS attacks can cause severe disruption to online services, resulting in lost revenue, reputation damage, and decreased customer trust.  DoS and DDoS are two different attack types, but the final aim of the attacker remains the same. DoS attacks use one computer (attack computer) and one victim. In contrast, DDoS attacks rely on more infected bots to carry out the tasks simultaneously to infect the target server, making it difficult to access the services for legitimate users. 

## Objectives
* Detection of Distributed Denial-of-Service (DDoS) attacks using a deep learning model.
* Utilization of the Long Short-Term Memory (LSTM) neural network architecture for feature selection and extraction.
* Use of the CICDDoS2019 dataset for training and testing the LSTM model.

## System Design
### Architectural Diagram
Fig showcases a DDoS attack detection system powered by a Long Short-Term Memory (LSTM) model. The system utilizes the CIC-DDOS2019 dataset, containing examples of both regular traffic and DDoS attacks, to train the LSTM model. By analyzing patterns in the training data, the LSTM learns to differentiate between normal and malicious network behavior. Once trained and evaluated, the system can classify new, real-time traffic as benign or a potential DDoS attack, enabling security personnel to take appropriate action.

## Methodology
1. Data Preparation:
* Dataset Selection: Curating a diverse and representative dataset is crucial for training and testing the DDoS detection models. The dataset should encompass various types of network traffic, including both benign and malicious traffic.
* Import and Distribution:The meticulous attention given to ensuring the random distribution of rows in the dataset is not just a procedural step; it's a preemptive measure against potential biases that might inadvertently influence the model during subsequent training and testing phases.
* Data Preprocessing: Before testing, the dataset undergoes preprocessing to ensure consistency, 
relevance, and suitability for input into the deep learning models. This may involve data cleaning, Feature Selection, Segregating data , label encoding, normalization.

2. LSTM Model Development:
Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) architecturethat is designed to overcome the limitations of traditional RNNs in learning and retaining longterm dependencies in sequential data.

<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.analyticsvidhya.com%2Fblog%2F2021%2F03%2Fintroduction-to-long-short-term-memory-lstm%2F&psig=AOvVaw2OE5TEBR5rPwzZY6gGyiJl&ust=1722514595136000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCODHzpah0YcDFQAAAAAdAAAAABAJ">

