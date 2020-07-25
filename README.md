TriMax
======

TriMax algorithm for computing maximal biclusters of similar values

Requirements
----------
* Boost C++ library (tested on 1.54.0)

Compiling and executing
---------
* For new install, install boost and g++ from this: https://nuwen.net/mingw.html

* Open CMD using C:/MinGW/open_distro_window
 navigate to the directory

* compile with 

> g++ -O3 *.cpp -o trimax

* Exec with 

> trimax datafile theta min_objects min_attributes max_objects max_attributes

> e.g.

> trimax sample.txt 2 0 0 4 5

theta = difference in values that would be considered for each column
min_objects = how many objects in a bic
min_attr = how many min attributes in a bic
max_objects = should not matter 
max_attr = should not matters
