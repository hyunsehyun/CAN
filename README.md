# CAN
Niro Control Area Network </br>
조이스틱을 이용한 차량 제어 CAN 통신 </br>

##Dependency
sudo apt-get install libsdl2-dev #need to install if you want to control with joystick </br>

###Run
sudo ip link set can1  up type can bitrate 500000 </br>
roslaunch can_package run.launch </br>


