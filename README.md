# Jetson PWM as HW Prototype

# abstract

Jetson's PWM(Pulse Width Modulation) to move 2 Servomortor with multi-thread.

<b>Jetson Nano and 2 Serbo mortor</b>

```sh
- JetPack > 4.6
- python3 3.6.9
- opencv 4.1.2
- Servo mortor :  TowerPro SG-90, 
```



# Setup

```zsh
# install GPIO
sudo bash setup/setpwm.sh

# setup pins for servo PWM
sudo bash setup/setpwm.sh
```

# References
- [jetson-gpio](https://github.com/NVIDIA/jetson-gpio/tree/master/samples)
- [Jetson Nano の 2 つのハードウェア PWM を使用してみた](https://qiita.com/kitazaki/items/2c9deb912f11106d1215)