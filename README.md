# mlsymdata
Dataset of symmetric graph drawings for machine learning projects, as well as other formats for analysis purposes.

For each graph different file types are available:

* dot
* png
* graphml 

Each file has the following nameformat:

{instance_id}-{[0=nonsym,1=sym]}_{instance_type}_{[0=nonsym,1=sym]}_{angle_of_rotation}.png

instance_type may be:
* SCR : symmetric with crossings
* SPR : symmetric with parallel lines (only)
* NPR: non symmetric with parallel lines
* NCR : non symmetric with crossings
* NRR : non symmetric random.

# graph size
* graph_4_8 contains graphs with a random number of vertices in the range [4, 8]
* graph_10_20 contains graphs with a random number of vertices in the range [10, 20]

each graph has a density in the range [1, 1.2]

