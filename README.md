  #Attribution Information: 

The Pacman AI projects were developed at UC Berkeley. The core projects and autograders were primarily created by John DeNero (denero@cs.berkeley.edu) and Dan Klein (klein@cs.berkeley.edu). Student side autograding was added by Brad Miller, Nick Hay, and Pieter Abbeel (pabbeel@cs.berkeley.edu). http://ai.berkeley.edu/project_overview.html
----------------------------------------------------------------------------------------------------------------------------
# AI
Project AI
# Demo
python pacman.py
# test Search
python pacman.py --layout testMaze --pacman GoWestAgent   
python pacman.py --layout tinyMaze --pacman GoWestAgent
# BFS Algorithm
python pacman.py -h     
python pacman.py -l tinyMaze -p SearchAgent -a fn=tinyMazeSearch      
python pacman.py -l tinyMaze -p SearchAgent       
python pacman.py -l mediumMaze -p SearchAgent       
python pacman.py -l bigMaze -z .5 -p SearchAgent        
python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs         
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5          
# UCS Algorithm  
python eightpuzzle.py   
python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs   
python pacman.py -l mediumDottedMaze -p StayEastSearchAgent     
python pacman.py -l mediumScaryMaze -p StayWestSearchAgent      
# Greendy Algorithm      
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic       
python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem      
python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem      
# A* Algorithm     
python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5     
python pacman.py -l testSearch -p AStarFoodSearchAgent      
python pacman.py -l trickySearch -p AStarFoodSearchAgent      
python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5      
# Approximate   
python pacman.py -l bigSearch -p ApproximateSearchAgent -z .5 -q      
