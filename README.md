# Amaze Maze

A teeny-tiny app which creates a random Perfect Maze and then solve it using 2 algorithms : 
  1) Depth First Search : 
  2) Breath First Search :

Technologies Used : Pygame 


### To Use This Code Follow these Steps :

#### 1) Clone this repository by running the command 
```
git clone https://github.com/MakeSchool-17/trees-mazes-python-monil-bansal.git
```

#### 2) Create a virtual environment, activate it and install the requirements by running the following command:
```
virtualenv -p /path/to/python3 venv
source venv/bin/activate
pip3 install -r requirements.txt
```
- In case you don't have ```virutalenv``` run the following command :
```
brew install mercurial sdl sdl_image sdl_mixer sdl_ttf smpeg portmidi Caskroom/cask/xquartz 
```
- For getting the */path/to/python3* run the following command
```
which python3 
```

#### 4) For running various parts of code follow these steps:
##### a) For just creating the maze run :
```
python3 generare_maze.py
```
#### b) For creating the maze and solving it using DFS (it is default algorithm)
```
python3 solve_maze.py
```

#### c) For creating the maze and solving it using BFS
```
python3 solve_maze.py bfs
```

## Final Results : 

![bfs](https://user-images.githubusercontent.com/31930832/119252518-68bdf700-bbca-11eb-91ea-2d634d6a09e6.gif)
(bfs)

![dfs](https://user-images.githubusercontent.com/31930832/119252683-306ae880-bbcb-11eb-8c8a-0f8ba4e38d59.gif)
(dfs)

