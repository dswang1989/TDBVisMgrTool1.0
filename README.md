Author: 
Dongsheng Wang (dswang2011@gmail.com), Hongyin Zhu (hongyin_zhu@163.com), Institute of Automation, CAS

project Name: 
TDB visualized Management Tool

Quicki tutorial: 
Open the GridBagDemo.java and run this, followed by a visuable window appeared. 
You first need to write down your local TDB path, or just a empty directory which will be created as a TDB. 
Then, you can upload ttl file or a directory with a group of ttl files. you can also query the TDB, or delete graph in TDB.

Motivation: 
Jena TDB is widely used to store tripes and RDF/OWL data. 
Since we did not find any visulized tool to manipulate jena TDB database, it is pretty unconvenient to check or look over the TDB we are dealing with. 
This is to assist all other works with TDB related.

Function: 
1. Create or Load a TDB from local path. 
2. Import RDF/OWL file into the TDB Note: both file and directory can be used here. When it comes into directory, it will iterate every ttl file. 
3. Delete a named graph from the TDB 
4. Use SPARQL to query and show result right in the panel

Limitation: 
When you query TDB, please add a limit like "limit 10000", because it does not support a large scale showing in screen.
