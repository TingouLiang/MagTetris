
# MagTetris: A simulator for fast magnetic field and force calculation for permanent magnet array designs

We propose a simulator named "MagTetris" that
can perform fast calculations for both the B-field and the magnetic
force simultaneously for a PMA consisting of cuboid magnets. It
does fast B-field calculations for arc-shaped/fan-shaped magnets with an arbitrary configuration as well.

![Logo](https://github.com/TingouLiang/MagTetris/blob/main/MagTetris%20Logo.png?raw=true)


## Authors

- Ting-Ou Liang (Major programming of MagTetris class): tingou_liang@mymail.sutd.edu.sg
- Junqi Yang (Visualization of magnetization): 22wd9202@student.gs.chiba-u.jp


## Related Publication
You can check the following publication to learn the framework and performance of MagTetris:

Ting-Ou Liang, Yan Hao Koh, Tie Qiu, Erping Li, Wenwei Yu, Shao Ying Huang,
MagTetris: A simulator for fast magnetic field and force calculation for permanent magnet array designs,
Journal of Magnetic Resonance,
Volume 352,
2023,
107463,
ISSN 1090-7807,
https://doi.org/10.1016/j.jmr.2023.107463.
## File List
- MagTetris.m - the complete class definition of MagTetris
- MagTetris_main.m - the scripts that contains examples for each MagTetris feature
- DrawMagnetization.m - a function to visualize the magnetization of all the magnets in a permanent magnet array

For the usage of magnetic field/force calculation and other functions, please check MagTetris_main.m for the details. Each section is an individual demo for different features.