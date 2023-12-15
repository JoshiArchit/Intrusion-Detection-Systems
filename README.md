# Intrusion Detection Systems
CSCI735 - Foundations of Intelligent Security Systems.<br>
Rochester Institute of Technology, Fall 2023

<h5> Project Overview </h5>
This course project deals with initial exploration and modelling of 
<b>Intrusion 
Detection Systems(IDS)</b>. As a part of the project we aim to utilise machine 
learning and AI 
techniques to model a misuse based and anomaly based Intrusion detection 
system (IDS).
The project is broken into 3 phases with corresponding documentation for the same.

***

<b>Dataset </b> - https://www.kaggle.com/datasets/galaxyh/kdd-cup-1999-data <br>
Location in project - [datasetKDD](data/datasetKDD) <br><br>
<b>NOTE -</b>
<ul>
<li>
All code in the project can be executed directly from the main() 
method. To run specific IDS functions one has to comment out the function 
calls in the script as the script is meant to be ran as a whole for metrics and 
continuity.
</li>
<li>
The code contains multiple dependencies on external libraries, a few of 
which are keras, tensorflow, pandas, matplotlib. Please review the code and 
make sure the dependencies are satisfied before execution.
</li>
</ul>

***

<h5> Project Phases</h5>
<ol>
1. <b>Phase 1 </b>

This phase focuses on identifying the data to work on, data preperation and 
cleaning as well as experimenting with current state of the art IDS like 
Snort and Suricata. From our initial exploration with the data set we had, 
we resorted to using classifier techniques to develop generic IDS in python.
<br><br>
Phase 2 Code - [idsClassifier.py](idsClassifier.py)<br>
Phase 2 Report - [Project_Phase_1.pdf](Project_Phase_1.pdf)

2. <b> Phase 2 </b>

This phase focuses on realising the shortcomings in Phase 1 and using 
Artificial Neural Networks (ANN) to recreate the IDS models for misuse and 
anomaly based IDS.<br><br>
Phase 2 Code - [annClassifier.py](annClassifier.py)<br>
Phase 2 Report - [Project_Phase_2.pdf](Project_Phase_2.pdf)

3. <b> Phase 3 </b>

This phase deals with comparing the approaches in Phase 1 and 2, drawing up 
statistics and addressing shortcomings and room for improvement.<br><br>
Phase 3 Report - [Project_Phase_3.pdf](Project_Phase_3.pdf)

</ol>

***
