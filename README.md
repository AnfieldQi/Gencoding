This project provides two components of Genius, a graph-based bug search framework. The first component is the raw feature extraction. The second is the online bug search engine.

1. The raw feature extraction is designed to achieve following two goals:
	-> Extract the control flow graph for each binary function
	-> Extract the attributes for each node in the graph
	
2. The online bug search engine is used for real-time search:
	-> It utilized localality sensitive hashing for indexing
	-> Nearest-neighbor search algorithm for search