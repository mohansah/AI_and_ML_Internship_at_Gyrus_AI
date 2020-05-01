# AI and ML Internship at Gyrus AI

## Project Description
This project has two parts:
1.	Collection of data from Motor using  STM 32 board.
2.	Development of AI models to detect anomaly in motor.

This is a group project consisting of two students. I was working on the second part of the project whereas the first part has been done by other student. The brief idea of the project was to collect sensor data via an STM32 microcontroller, process the data to calculate FFT on the collected data, and finally read the FFT data into a csv file. This file is then converted into a dataset to train an AI model for anomaly detection. The model is then run on the STM32 board. The result from the model is sent to a remote server via MQTT protocol.

## Work Completed
1.	Explored about the concept of AWS and understood how to perform analytics there to create the dataset.
2.	Explored about how to send data to the AWS through python coding.
3.	As per company’s instructions, got familiar with opencv (python library for image processing), explored the library and developed a people counter which  count the number of people crossing a road.
4.	Explored about the various neural network architecture like CNN, LSTM etc. Till now I developed CNN network, LSTM network and combination of both i.e., CNN-LSTM network for anomaly detection and all are performing well.

## Work yet to be done
1.	The company directed to do experiment with multiple network architecture so that we come to a particular network which will work with high accuracy and for this my next job is to develop a ConvLSTM network which is a variant of LSTM containing a convolution operation inside the LSTM cell.
2.	After the selection of particular network architecture, we will implement it on STM32 for anomaly detection.
3.	Creation of a dashboard which will display the output the project.
