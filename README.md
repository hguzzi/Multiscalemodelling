# Node centrality analysis on Protein Contact Network of the SARS-CoV-2 Spike Protein.

Protein Contact Network is an unweighted graph rappresentation of the protein: the nodes of the graphs are the amino acids and exists an edge that connect two nodes i and j only if the euclidean distance between this two amino acids is between 4 Angstrom (only non covalent interactions) and 8 Angstrom (only significant interactions). The distance between two aminoacids i and j is approssimated by the distance between the Alpha Carbon of the amino acids. The user can modify the only covalent (min) and the only significant (max) threshold distance for PCN construction. 

![image](https://user-images.githubusercontent.com/87126937/162151753-43c6157b-028a-45e2-9aeb-dafd912d4162.png)

![image](https://user-images.githubusercontent.com/87126937/162151714-bf5ce554-14ad-4100-b4e9-6d95af19bca0.png)

PCN global (like graph diameter) or local descriptors (like node centrality measures) are useful to model and analyse protein functions. 

Spike protein variants studied: Wild Type (no mutations) and variants of concern Omicron and Delta.

Spike protein conformation studied: open state, closed state and complexed with ACE2 human receptor.