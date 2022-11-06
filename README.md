# move_to_waypoints
## Dependencies
```bash
# install BehaviorTree.CPP deps
$ sudo apt-get install libzmq3-dev libboost-dev libncurses5-dev libncursesw5-dev

# clone and build repo
 $ git clone -b v3.8 https://github.com/BehaviorTree/BehaviorTree.CPP.git
 $ mkdir build
 $ cd build
 $ cmake ..
 $ make
 $ sudo make install

# then clone and build the main repo
$ cd ~/
$ git clone --submodule-recursive https://github.com/Efekurdoglu/move_to_waypoints_behavior_trees.git
$ cd move_to_waypoints_behavior_trees
$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./main
```
