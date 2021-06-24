# ant-colony-optimization
Solving TSP with ant colony optimization.
# explanation
- solved TSP with ant colony optimization with berlin59 dataset.
- i put my analysis for each parameter but it is in persian.
# executation
run with python 3.
# algorithm
First, we randomly place the number of ant populations in different cities. Then, at each stage, all the ants go to one of the permitted paths connected to that city with the said probability, and a fixed number, such as k, is poured along each edge of the pheromone path, and after all the ants, a They chose the path. The pheromones are poured on the edges and the previous pheromone evaporates with a percentage of Evap. This algorithm continues until each ant finds a Hamiltonian cycle.
- Probability Function: The edges connected to each vertex have the pheromone probability of that edge divided by the sum of the pheromones of all the edges connected to that vertex.
- Evaporation: After each ant moves one, all the pheromones on the edges remain as Evap..
- Pheromone: Each time an ant passes over Bali in size
k / Li is added to the pheromone of that edge, where Li is the fixed length and k is a fixed number.
- End of algorithm: The algorithm stops after number of iteration times.
