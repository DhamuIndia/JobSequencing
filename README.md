# JobSequencing
Sequence the jobs based on dependency

Input is through the txt file in the path src/com/pckg/jobsequence/input.txt

Example Input format

a =>  
b => c  
c => a  
d => e  
b => a 


The solution to sort the jobs is to build a Directed Acyclic Graph and do a Topological Sort to get the jobs in sorted seqeunce.

Steps to solve this challenge

Step 1 - Create classes Edge, Vertex which are the attributes of graph.  
Step 2 - Creata a class Graph with Edges and Vertcies as data memebers.  
Step 3 - Read the input from the file, Parse it and build the Directed Acyclic Graph with Vertices and Edges.        
Step 4 - Do a topolical sort on the Directed Acyclic Graph to get the results in sorted order.

To Run the Application give the input in input.txt file and run the project as java application to see the job sequence output in console.
