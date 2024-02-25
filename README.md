<h1 align="center"> Framework SSL </h1>


***SSL System***


- [x] Ubuntu 20.04




# Linux:

Step 1
```
git clone https://github.com/robotics-erlangen/framework.git
```
Step 2
```
sudo apt install protobuf-compiler libprotobuf-dev qtbase5-dev
                 libqt5opengl5-dev g++ libusb-1.0-0-dev libsdl2-dev libqt5svg5-dev libssl-dev -y
```
Step 3
```
mkdir build && cd build
cmake ..
make
```

```
sudo cp data/udev/99-robotics-usb-devices.rules /etc/udev/rules.d/99-robotics-usb-devices.rules
```

```
make install-menu
```
