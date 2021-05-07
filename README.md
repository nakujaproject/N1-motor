# N1-motor
`
 Reporsitory that holds files related to the N1 motor development for the Nakuja Project`

![GitHub last commit](https://img.shields.io/github/last-commit/nakujaproject/N1-motor) ![GitHub repo size](https://img.shields.io/github/repo-size/nakujaproject/N1-motor) ![GitHub_contributors](https://img.shields.io/github/contributors/nakujaproject/N1-motor) ![GitHub_user_stars](https://img.shields.io/github/stars/nakujaproject?style=social) ![Twitter Follow](https://img.shields.io/twitter/follow/Nakuja6?style=social)

***
## Table of Contents

1. [Description](#description)
2. [Goals](#goals)
3. [Methodology](#methodology)
4. [Key Design Parameters](#key-design-parameters)
5. [Directories](#directories)
6. [Technologies](#technologies)

***

## Description

The N1 motor is a Solid Rocket Motor developed by the Nakuja Project. The motor is meant to be used on a small launch vehicle. The purpose of the motor is to offer propulsion to a rocket that will be recovered in so doing put into practise the skills of armature experimental rocketry


## Goals
The N1 motor is expected to propel the launch vehicle to a hieght of between `50 to  100m`


## Methodology
The motor is made up of one of three propellant combinations:
> + KNSU(Potassium Nitrate + Sucrose)
> + KNDX(Potassium Nitrate + Dextrose)
> + KNSB(Potassium Nitrate + Sorbitorl)

The three fuels are to be cast to form free standing grains which are to  be assembled in a pvc pipe along with a nozzle and endcaps.
This repo contains design, simulation data as well as results obtained from static tests conducted on different grains and parameters

## Key Design Parameters
The following factors are taken into consideration when designing the N1 motor:
- Performance- The motor must provide enough thrust to take the launch vehicle to a minimum of 50m
- Chamber Pressure - The chamber pressure must be within the workable range of the UPvc pipe we are currently using
- Rocket Airframe design-  the rocket must fit into the designed launch vehicle

## Directories
The following is a list of the contents of each directory in the reporsitory:
+ [Drawings](/Drawings) - contains all the design drawings for the N1 motor
+ [Proposed Final Spec](/Proposed%20Final%20Spec) -contains design simulations to obtain specifications for final motor
+ [Tests](/Tests) -contains all data obtained from static tests

## Technologies
The design and simulation of the N1 motor uses the following software:
1. SRM.xls obtained from the nakka rocketry website. Link attached [here](https://www.nakka-rocketry.net/soft/SRM_2014.1.zip)
2. openMotor- [Link](https://github.com/reilleya/openMotor)
3. OpenRocket - [Link](https://openrocket.info/)
