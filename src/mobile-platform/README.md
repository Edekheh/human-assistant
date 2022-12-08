# Additional packages needed for using the package

To use this package, it is important to install package consisting dingo robot by clearpath by running and building these packages in main src folder

'''
git clone https://github.com/dingo-cpr/dingo.git
git clone https://github.com/dingo-cpr/dingo_simulator.git
git clone https://github.com/dingo-cpr/dingo_desktop.git

cd ..
rosdep install --from-paths src --ignore-src
catkin_make
source devel/setup.bash

'''

