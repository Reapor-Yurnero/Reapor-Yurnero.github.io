---
title: "Brick & Building Operating System"
tags:
  - "Smart Building"
  - "Operating System"
date: Oct 2019 - Present
# venue: DOTA2
authors:
  - name: "With Jason Koh, Dezhi Hong, Rajesh K. Gupta, and Gabe Fierro."
path: "research/brick_bos"
excerpt: In this project, we are aiming to create a Building Operating System (BOS) providing an interface between the underlying building hardware (e.g. HVAC system, light, sensor) and users (e.g. developers, building managers, residents). With this interface, developers can create applications to make the life of building managers and residents easier. Paper undersubmission to ICCPS 2024.
selected: true
cover: "./preview.png"
links:
  - name: "ICCPS24 Paper"
    file: "./24ICCPS_SBOS.pdf"
  - name: "BuildSys20 Poster"
    url: "https://dl.acm.org/doi/10.1145/3408308.3431113"
  - name: "Repo (public)"
    url: "https://github.com/BrickSchema/brick-example-server"
  - name: "BuildSys23 Paper (BEAR)"
    url: "https://dl.acm.org/doi/10.1145/3600100.3623740"
  - name: "RLEM22 Paper (B2RL)"
    url: "https://dl.acm.org/doi/abs/10.1145/3563357.3566164"
priority: -20
---

## Introduction

Building Operating System (BOS), just as the traditional operating systems for computers and mobiles, provides an interface between the underlying hardware (e.g. HVAC system, lights, sensors) and users (e.g. developers, building managers, residents). With this interface, developers can create applications so that building managers can use these applications to facilitate their work and residents can control their surrounding climate, electrical appliances smartly and conveniently. On top of [Brick Schema](https://brickschema.org/), we are building such a fully functional BOS composed of timeseries database, brick database, authorization, and so on, which is called Brick Server and its extended version Playground.

Brick Server / Playground is

- a minimal but fully functional Building Operating System (BOS),
- an interface for Brick applications,
- an emulator of a building for Brick applications development,
- a demonstration of general methods to integrate your system with Brick, and
- a testbed for new functions in Brick.


## Ongoing Work

Although this project is in the context of Smart Building, many problems that span across a wide range of areas are of our particular interest. 
1. How to do authorization and authentication properly in this complex multi-layer privilege model? (OS)
2. How to scale well to fit e.g. a campus, tens of buildings, 10k data points, thousands of users? (Distributed System)
3. How to guarantee the security and privacy of these sensitive data? (Security, Privacy and Cryptography)
4. How to facilitate our platform to help control and monitor the risk of COVID19 spread caused by indoor gatherings? (Smart Building) See our [BuildSys20 Poster](buildsys20postersdemos-final8.pdf) for more details.


