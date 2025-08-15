---
layout: post
title: Turbo Taskforce
date: 2023-08-01 00:00:00
description: Chaos couch co-op - assemble an electric remote race car and together make the best time on the track!
img: TurboTaskforce.png # Add image post (optional)
tags: [Unity3D, Game Design, Local Coop, Promotional] # add tag
---
<iframe frameborder="0" src="https://itch.io/embed/2111899" width="900" height="167"><a href="https://marlogamedev.itch.io/turbo-taskforce">Turbo Taskforce: Remote Racing Ruckus by Marlo, FreezzeChills, Aboudi.A, TheTiredGuy5, Sypsic, Flower</a></iframe>

## My work on this project
As the main Game Designer on this project, I prototyped many of the systems and guided the team in making the decisions around gameplay mechanics. I outlined two examples, the part system and the control room controls, further below.

My biggest learning in this project was how difficult and important it is to bring the individual inspirations of the team members and the game vision together to empower everyone in their contribution and build a coherent game experience. I think the result of the project illustrates how much I grew in this regard.

It makes me happy to see that the team worked so well together that more projects in the same constellation are underway. 

## Game Description

Get your friends together, it is time to show your cooperation skills in constructing and controlling an electric remote race car. Time is of the essence when getting your car ready: you only have 90 seconds to build it and then get the best time on the track by piloting it from the control room.

The car is built out of different components. Use the ones that lie around and print everything else with the powerful part printer. Can you get all the necessary parts together to have a functioning car? If you forgot the brakes, you better be careful on the track! Or maybe even the steering? Little chance you make it past the first curve.

When building is done, it is time to put it to the test. Your team will be in the control room, steering the car from afar. All components that you built in have a station that gives you control over that part of the car. Jump into the steering wheel and keep the car on track or hit the boost at the right time giving that nudge needed for a new record. But beware, while everyone can do everything, nobody can do all of it at the same time.

Communication is key to push all the buttons that brings your car over the finish line. Will your team of friends have what it takes to succeed at building an electric remote race car?

Turbo Taskforce is a game developed by a group of 6 students to give students a taste of what it is like to join the real electric car building competitions that happen all around the world. As a couch co-op game, it is designed to be a short experience at a convention or booth but does not fall short if you get your friends together at home in the combined effort to put up a new record.

<iframe width="896" height="504" src="https://www.youtube.com/embed/DeYvwYXsYok?si=FWDx6PQKxCeIpzjc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## The Project

Turbo Taskforce was developed with a team of 6 students over 5 months. The game was made specifically for the electric student formula team Hanze Racing Division as a tool to introduce new students and sponsors to their project work, as well as increasing the awareness about the team around campus. In the team I fulfilled game design, programming and project management roles.

On the student festival, my team and I won 3 of the 7 game awards with it, for best overall game, most captivating gameplay and innovation. You can find and download the game for free on the itch.io webpage.

## Work process on car parts

One of the big systems that I worked on were the parts that got put on the car. It shows very nicely the whole process that I run through when developing a feature.

In this case, the general idea of what the parts were supposed to do were already laid out with the game concept: somehow represent the electric car building process and give the players ownership on what they build without becoming too complex.

![Part Interaction Diagram]({{site.baseurl}}/assets/img/TurboTaskforce/PartsDiagram.png)
> Initial diagram of part interaction in the car.

I laid out how this could look like. With background research on the parts of an electric car and interviewing the student formula team, I formed an idea how parts could interact and which purpose each of them serves. Distilling this down further on the biggest impacts and most promising effects, the core list of parts was born.

Early tests showed it worked well. However, it showed that players were already well occupied with just building a working car. I removed most interdependency of parts, meaning all (missing) parts had a direct, visible impact on the car’s functionality – except for the wheels.

During the whole process, with the implementation into the game, I discussed the system and gathered feedback from the team, as well as from playtests. 

![GDD Car Parts 1]({{site.baseurl}}/assets/img/TurboTaskforce/CarParts_Section1.png)
> GDD for the car parts with priority coloring.

![GDD Car Parts 2]({{site.baseurl}}/assets/img/TurboTaskforce/CarParts_Section2.png)
> GDD for the car parts with priority coloring.

A feature that we delayed, that could add more depth with marginal difficulty increase for beginners in the future, is area of effect for some car parts. This would allow players to control which wheels are affected by engines or steering.

## Building the control room
Closely connected to the parts and in a similar iterative fashion, I designed the control room. The two goals here were to connect the parts to how the car drives and make steering a coop task. Inspiration came from games like “Human Fall Flat”, in which at one point the players must drive a truck. One player would hold onto the steering wheel and another was in charge of the brake.

At first, I experimented with different control surfaces, like pedals and wheels. However, pedals alone were boring, even with gradient controls. With the game based around moving around, potentially getting into each other’s way or “trolling” someone to prevent them from doing their task, the “hamster steering wheel” and the “power stations” were born. The power stations represent battery and engine, where inserting the limited charge batteries into the engine tube would function as the gas pedal as well.

Through play tests, I adapted the steering wheel from a direct translation of steering angle into a dampened version, a bit like trying to run away from a post that you are attached with a rubber band. This created a nice mastery curve over one racetrack completion, fitting to our intended short session experience.

![Control Room Prototype 1]({{site.baseurl}}/assets/img/TurboTaskforce/ControlRoomPrototyping1.png)
> First prototype of the control room.

![Control Room Prototype 2]({{site.baseurl}}/assets/img/TurboTaskforce/ControlRoomPrototyping2.png)
> Iteration of the control room with more parts.