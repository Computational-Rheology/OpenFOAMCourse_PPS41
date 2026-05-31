# **Introduction to OpenFOAM® Computational Library and Design of Profile Extrusion Dies**
## João Miguel Nóbrega and Mohammadreza Aali
## University of Minho and Johannes Kepler University of Linz

# System Setup


## 1-Introduction
![Introduction](./Covers/Slide1.JPG)

[Video](https://youtu.be/JfdOgG3EF_w)


## 2-Windows Subsystem Linux
![Windows Subsystem Linux](./Covers/Slide4.JPG)

[Video](https://youtu.be/aXJjHlPzC7c)

```
wsl –-install -d Ubuntu-24.04
```

## 3-Visual Studio Code
![VSCode](./Covers/Slide5.JPG)

[Video](https://youtu.be/j1cIAIaGunY)

Installation website: https://code.visualstudio.com/

## 4-OpenFOAM v2512
![OpenFOAM](./Covers/Slide6.JPG)

[Video](https://youtu.be/n6GUmFz95oQ)

Installation website: https://gitlab.com/openfoam/core/openfoam/-/wikis/precompiled/debian

commands to run
```
# Add the repository
curl -s https://dl.openfoam.com/add-debian-repo.sh | sudo bash

# Update the repository information
sudo apt-get update

# Install preferred package. Eg,
sudo apt-get install openfoam2512-default

# Use the openfoam shell session. Eg,
openfoam2512

# Setup the variables expansion
echo 'shopt -s direxpand' >> ~/.bashrc 
```
## 5-Paraview 6
![Paraview](./Covers/Slide7.JPG)

[Video](https://youtu.be/gdrhQ07d9mU)

Installation website: https://www.paraview.org/download/


## 6-FreeCAD 1.1.1
![OpenFOAM](./Covers/Slide8.JPG)

[Video](https://youtu.be/p5oqfOFpeV4)

Installation website: https://www.freecad.org/downloads.php