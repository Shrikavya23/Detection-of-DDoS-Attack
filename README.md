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

