# Using Drones as Reference Sensors for Neural-Networks-Based Modeling of Automotive Perception Errors

This repository holds additional figures to the mentioned [IEEE IV](https://ieee-iv.org/) 2020 publication, which is available at:
- arXiv: Link will be included.
- IEEEXplore: Link will be included.

![Paper front page](PaperFrontpageSnippet.PNG)

To cite the following graphics, please cite the paper itself. It includes a link to this repository. Bibtex:
```
@InProceedings{Krajewski2020UsingDrones,
  author    = {Krajewski, Robert and Hoss, Michael and Meister, Adrian and Thomsen, Fabian and Bock, Julian and Eckstein, Lutz},
  booktitle = {2020 IEEE Intelligent Vehicles Symposium (IV)},
  title     = {Using Drones as Reference Sensors for Neural-Networks-Based Modeling of Automotive Perception Errors},
  year      = {2020},
}
```

## Short Background

Vehicles are perceived by both a lidar-based system under test (SUT) and a UAV-based reference measurement system (ref).
For both systems, the vehicle state vector <img src="https://render.githubusercontent.com/render/math?math=\mathbf{x}=(x, y, vx, vy, w, l, \Psi)^T"> consists of positions, velocities, width, length, and orientation angle. 
The following graphics show the errors <img src="https://render.githubusercontent.com/render/math?math=\mathbf{E} = \mathbf{x}_{SUT} - \mathbf{x}_{ref}"> of the lidar-based objects with respect to the reference. These errors can be
- **observed** in actually measured data
- **predicted** by the neural-networks-based Gaussian error model. The inputs to this model can be:
  - reference data that actually got measured
  - artificially generated reference data.

Please read the paper for more information.


# Figures

## Errors observed and predicted on *measured* reference data

### Position x

<img src="figures/Ex_observed.png" width="700" height=""/>
<img src="figures/Ex_predicted.png" width="700" height=""/>

### Position y
<img src="figures/Ey_observed.png" width="700" height=""/>
<img src="figures/Ey_predicted.png" width="700" height=""/>

### Velocity vx
<img src="figures/Evx_observed.png" width="700" height=""/>
<img src="figures/Evx_predicted.png" width="700" height=""/>

### Velocity vy
<img src="figures/Evy_observed.png" width="700" height=""/>
<img src="figures/Evy_predicted.png" width="700" height=""/>

### Width
<img src="figures/Ew_observed.png" width="700" height=""/>
<img src="figures/Ew_predicted.png" width="700" height=""/>

### Length
<img src="figures/El_observed.png" width="700" height=""/>
<img src="figures/El_predicted.png" width="700" height=""/>

### Orientation angle
<img src="figures/Epsi_observed.png" width="700" height=""/>
<img src="figures/Epsi_predicted.png" width="700" height=""/>


## Errors predicted on *artificial* reference data

### Position x
<img src="figures/MUx_predicted.png" width="700" height=""/>

### Position y
<img src="figures/MUy_predicted.png" width="700" height=""/>

### Velocity vx
<img src="figures/MUvx_predicted.png" width="700" height=""/>

### Velocity vy
<img src="figures/MUvy_predicted.png" width="700" height=""/>

### Width
<img src="figures/MUw_predicted.png" width="700" height=""/>

### Length
<img src="figures/MUl_predicted.png" width="700" height=""/>

### Orientation angle
<img src="figures/MUpsi_predicted.png" width="700" height=""/>
