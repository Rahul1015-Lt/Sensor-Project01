## Machine learning sensor project
Sensor Fault Detection Project
In electronics, a wafer is a thin slice of semiconductor, such as crystalline silicon (c-si), used for the fabrication of integrated circuits and in photovoltaics to manufacture solar cells. The wafer serves as the substrate (serves as a foundation for the construction of other components) for microelectronic devices built upon the wafer.

Fabrication: the process of creating ICs on a semiconductor material, typically silicon. This process is highly complex and involves multiple steps to build the tiny electronic circuits that are used in almost all modern electronic devices, such as computers, smartphones, and other gadgets.


Multiple wafers for Mass Production: In semiconductor manufacturing, many wafers are processed simultaneously to produce a large number of ICs. Each wafer typically contains hundreds or even thousands of identical circuits(chips) that are later cut out and used in electronic devices

We have ICS and chips placed on wafers

Problem statement:
Objective: Develop a machine learning model to predict the quality of semiconductor wafers as either "good" or "bad" based on sensor readings collected during the fabrication process.


Details:
Inputs (feature): The dataset consists of 590 sensors reading for each wafer. These readings capture various environmental and process parameters during the fabrication


Output(Target): The target variable is labeled as"good/bad", where 1 indicates "good" & -1 indicates "bad".


Goal: The goal is to build a classification model that can accurately predict whether a wafer is good or bad based on sensor readings. The prediction can help in early detection of defective wafers, improving yield, and reducing waste in the semiconductor manufacturing process.

Machine Learning Task:
Type: Supervised Learning(classification)
Model Type: Binary Classification Model


Post Production Inspection:
Batch Testing:


Logging setup

LOGGING is crucial for tracking events that happen when the application runs
This helps in debugging and monitoring the application behaviour

Requirments
Directory
file structure
path
