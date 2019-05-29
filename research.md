# Brent Research Progress

## Project Ideas

1. Information Sharing at Intersections 
	* Problem: Given an asymmetric intersection with occlusions, can one vehicle send information to another vehicle to communicate risk?
	* Can we solve this problem while also accounting for delays and communication latency?
	* Metrics
	* References
		* Sampling Based Representations with Communication Constraints (Alex Ihler): https://pdfs.semanticscholar.org/7b74/7e633ff34e76b9b64f402264282c6f31bc84.pdf
		* Particle Filtering with Communication Constraints (Alex Ilher) https://www.ics.uci.edu/~ihler/papers/ssp05.pdf
2. Temporal Predictions of Risk at Intersections
	* Problem: Can we come up with a model that takes as input observtaions of vehicles on the road, and outputs some risk metric? 
	* Idea: Extend the approach by Steve et al in IROS in order to accommodate some sensor observations, in addition to high level vehicle detections.
	* Implementation: Can we use graph neural networks defined over the road segment model from the paper? Can this be augmented with sensor data, i.e. camera or Lidar?
	* References
		* https://github.com/deepmind/graph_nets.git


