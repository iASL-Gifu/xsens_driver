ROS 2 driver for XSens MT/MTi/MTi-G devices. It is based on the ROS 1 driver made by Francis Colas (see https://github.com/ethz-asl/ethzasl_xsens_driver).

** Some useful commands to enable serial communication

```
sudo adduser $USER dialout
```

where `$USER` is the username.

## Environmental Settings
please install pyserial

```bash
pip install pyserial
```

if you get numpy error, please this command

```bash
pip uninstall -y numpy && pip install --ignore-installed numpy==1.23.4
```

if you get transforms3d error, please this command
```bash
pip install tarnsforms3d
```