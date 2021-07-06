---
title: "Stupid Planets"
date: 2021-07-06T22:59:23+09:00
draft: false
categories: [projects]
tags: [Python, C#, Procedural Generation, Unity]
---

### Developer

Global Nominee for NASA's Space Apps Challenge 2020. A colonization game that (semi) accurately simulates thermodynamic and physical properties of exo-planets and star systems.

https://2019.spaceappschallenge.org/challenges/planets-near-and-far/build-planet-workshop/teams/quinn-the-buffalo/project

 Stupid planets aims to recreate a sandbox-like environment of procedural star systems and exoplanets. The aim of Stupid Planets is to provide an educational experience on the basic elements needed for life and colonization on exoplanets through scientific modelling, physically based orbital movement and loose modelling of chemical compositions and interactions.

![](/stupid.PNG)

 The focal point of the game play mechanic revolves around the mad and intricate balance of several different factors including the chemical composition of planets, temperature, its orbital radius, and its mass. Players have the ability to colonize planets and get real time feedback on why their colonization efforts failed/succeed or they can wait for life to randomly develop on planets. However, players need to be aware that changing one variable could lead to an unforeseen reaction of circumstance that may ruin the planet entirely. 

  We calculated the temperatures of the planets via multiple factors involving the sun's mass, the planets' distances to the sun, as well as their chemical makeup and terrain. By altering these elements, the player is able to create a potentially habitable planet. The calculations were taken from a number of online sources, and changed to suit our purposes. Some values that are essential to our calculations such as the albedo values of these simulated planets cannot be calculated so we approximated it based on known planets and their characteristics.

   We implemented another method for temperature. We analyzed the thermal conditions at a planet's surface. The power on the surface per area is related to a multitude of factors, including the temperature and the radius of the star, the distance between the star and the planet, and the percentage of energy actually arrived at the planet (which is related to the chemical composition of the atmosphere). The power emitted by the planet per area is related to the surface temperature and the absorption of the atmosphere. We looked up some graphs of absorption curves (https://www.sciencedirect.com/science/article/pii/S2405844018327415) and estimated the absorption percentage at different frequencies for some common atmospheric chemicals.Then we combined them with the black-body radiation curve to obtain the planet's surface temperature at which the power by the surface per area equals the power on the surface per area.

  A large part of Stupid Planets is its ability to generate completely procedural planets based on a variety of properties. Taking inspiration from real categories of exoplanets, several types of planets may appear in any given solar system. Earth-like planets appear in the habitable zone with usually habitable conditions while snowy and rocky worlds exist on the outer bounds of the system. Each terrain is generated through a layered Perlin noise based on the chemical composition, orbital radius, properties of the sun, etc.


