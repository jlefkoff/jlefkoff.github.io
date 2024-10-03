+++
title = "Fleet Robotics"
date = "2024-10-03"
portfolioCover = "img/fleet.jpg"
type= "portfolio"
weight=1
+++

*Fleet Robotics is a 2-year old startup that makes underwater robots that inspect and clean ship hulls while underway.*

![](https://images.squarespace-cdn.com/content/v1/65deb02e8d9c8d2808be3730/73fd956e-98c7-4fcc-98cb-25eb5ca00595/Fleet_StationV2_11.jpg)

## Ultrasonic Sensing System
I had the opportunity to work on a project integrating vision and on-craft image processing into the existing aerial platform.

#### Problem
The Fleet Robotics system operates in an incredibly harsh environment; the open ocean. To sense and feel autonomously, as well as collect critical inspection data for ship operators, the robot requires a variety of complex sensor suites.

Currently, this NDT (non-destructive testing) data is only collected at a handful of points once or twice a year on *an entire container ship*. With Fleet's platform, this is increased to millions of data points every day of operation.

One of these NDT sensor techniques is ultrasound. This technology uses transducers that pulse high frequency sound waves and listen for reflections to detect weld-lines, paint thickness, and steel impurities. This was the best way to acquire the data that we desired.

#### Action

I evaluated a variety of ultrasound platforms including open and closed-source solutions. I looked at transducer and probe parameters specific to Fleet's applications.

After determining a reliable solution for the desired measurement parameters, I began to develop a full-featured software integration. This allows for remote data acquisition, as well as real-time information to the rest of the robot subsystem on what the ultrasound subsystem is "seeing."

#### Result

The ultrasound system I developed is a successful add-on to the existing robotics platform and allows for newfound insights into ship health. The quantity of data this platform is able to gather is unprecedented and allows preventative maintenance to ensure ship reliability that was previously impossible.
