# Process-Discovery-and-Variant-Analysis
Study on the BPIC-17 Loan Application Event Log

## Abstract
The aim of this report is to present findings and insights from the analysis of the BPIC-17 event log, which documents the loan application process of a Dutch financial institution. The analysis combines automated process discovery with manual refinement to understand the main behavioral patterns and build an interpretable process model. The Inductive Miner and Heuristics Miner algorithms provide initial process models whose limitations become clear through differences in fitness and precision, motivating a structured refinement procedure. By focusing on frequent activities and removing infrequent paths, the final BPMN model achieves a balanced quality profile with a fitness of 0.87 and a precision of 0.73. The report also explains why pm4py and the Celonis Variant Explorer show different variant counts, pointing out that Celonis reduces repeated activities and therefore reports fewer variants. Overall, the results demonstrate how combining algorithmic discovery with structured manual reasoning leads to a clearer and more realistic process model. 

## Dataset

Please download the dataset package “BPI Challenge 2017_1_all” from the official website (https://ais.win.tue.nl/bpi/2017/challenge.html) and place it in this project’s root directory.
