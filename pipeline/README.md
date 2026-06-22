executar-ho tot fora de visual studio, en una terminal apart

cada cop que s'entra, executar els següents commands a la carpeta ws_tamp/src

echo "source /opt/ros/jazzy/setup.bash" >> ~/.bashrc
source ~/.bashrc
colcon build --symlink-install
source install/setup.bash

el exe també s'ha dexecutar a la mateixa terminal