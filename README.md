# Device Tree for Nokia 2 (e1m)

The Nokia 2 (codenamed _"e1m"_) is a low-end smartphone from Nokia.
It was released in November 2017.

| Basic                   | Spec Sheet                                       |
| -----------------------:|:------------------------------------------------ |
| CPU                     | Quad-core 1.3 GHz Cortex-A7                      |
| Chipset                 | Qualcomm MSM8909v2 Snapdragon 212                |
| GPU                     | Adreno 304                                       |
| Memory                  | 1 GB RAM                                         |
| Shipped Android Version | 7.1.1                                            |
| Storage                 | 8 GB                                             |
| Battery                 | Non-removable Li-Po 4100 mAh battery             |
| Display                 | 720 x 1280 pixels, 16:9 ratio (~294 ppi density) |
| Camera (Back)           | 8 MP, AF, LED flash, 720p@30fps                  |
| Camera (Front)          | 5 MP                                             |


![Nokia 6.1](https://cdn2.gsmarena.com/vv/pics/nokia/nokia-2-1.jpg)


## Build instructions

```
# Compiling
$ . build/envsetup.sh
$ lunch omni_e1m-eng
$ make -jx recoveryimage

```

**Kerenl Source**: Ask HMD Global to provide it.
