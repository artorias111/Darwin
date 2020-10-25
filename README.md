# Darwin
A simulator for natural selection, inspired by Charles Darwin and genetic algorithms
Environment:
Populators
Food (Organisms can be food)
Climate

Directories: (View readme in the directory for specific instructions)
Species: Contains all the different types of organisms as Python classes
Food: Different types of food, can include classes from species as food. Non organism food should be specified for specific terrains. 
Terrains: Different terrains(climate) where these organisms will (Learn to?) survive

1. choose your species
2. choose your terrain

3. Watch them grow, live a life, make families, and perish :(

Factors: 
1. Initial population:
each species has 5 genes in a single chromosome. (fixed)
Each element in gene[5]: 1 if gene is expressed, 0 if not expressed  
 
2. Fitness function: 
Give a score to each individual to determine its ability to survive in the environment

3. Selection:
Two individuals (parents) are selected based on their "fitness score". Ones with similar scores are considered for reproduction. 

4. Crossover:
For each pair of individuals mated, A point of crossover is randomly chosen, and the genes are exchanged at that point 

5. Mutation:
Some genes can randomly undergo a shift from 0 (not expressed) to 1 (expressed). Different probabalities are assigned based on the terrain. 
