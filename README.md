# CSE 3521 Homework 1
This assignment comes from [UC Berkley](https://inst.eecs.berkeley.edu//~cs188/pacman/home.html), and the only files I changed are `search.py` and small changes to `util.py`

Commands to try:

`python py/pacman.py`

`python py/pacman.py --layout tinyMaze --pacman GoWestAgent`

`python py/autochecker.py`

`python py/pacman.py -l mediumMaze -p SearchAgent -a fn=dfs`

can change dfs to bfs or ucs for the different algorithms

`python py/pacman.py -l mediumMaze -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic`

If graphics are not working:

`python py/pacman.py --layout tinyMaze --pacman GoWestAgent --textGraphics`
