---
layout: "post"
categories:
- "Applied Design"
title: "Building a Better Watering Setup for the Farm"
feature_image: "/assets/watering-head-installed.jpg"
---

At work, we have a large batch mixer that is used to mix sawdust with supplements and water before it is bagged, sterilized, and inoculated. Until recently, the prevailing solution used to add water to the batches was a garden hose with holes slashed in it. This was a pain; it sprayed water in wild directions and was clearly not dispersing the water evenly over the mixture. I finally got around to making a replacement, and it just so happened that the hose got sucked into the mixer the day after I had brought it in for test fitting. But the water-dispensing part of this project isn't really the point, although it has improved efficiency by watering the batches more consistently. The biggest reason I finally decided to do this was because it was the perfect chance to brush up on my CAD and design skills.

The first problem I had to solve for this project was that I needed to drill 20 holes, evenly spaced 2" apart, all in line with each other along both of the lengths of PVC pipe that stretch across the mixer (leftmost pipes in the above photo). My solution was to design a simple, 3D-printed jig to hold a length of pipe horizontally on a table, with a top half that fits over the pipe and has holes for measuring and marking the hole positions.


{% include figure.html image="/assets/hole-marking-jig.jpg" caption="The marking/drilling jig (purple) and the bottom half of a pipe clamp (green)" position="left"%}


I also needed to design a pipe clamp, two of which would support the pipe on a drill press and ensure all the holes were centered. These took a little longer to design than the marking jig, but I was able to make a pair that worked after only one failed prototype. They hold the pipe the same distance from the table as the marking jig, so they serve as a helper when marking holes and then the bottom half of the marking jig supports the pipe under the drill bit. This made drilling the holes easy as I just had to center the pipe under the drill bit, tighten the clamps, and follow the markings (while checking that the previously drilled hole was still vertical).


{% include figure.html image="/assets/drilling-jig.jpg" caption="The clamps allowed a tight sliding fit over the pipe while still clamped firmly to the table" position="left"%}


After drilling the business end of the contraption, putting together the rest of the PVC was straightforward:


{% include figure.html image="/assets/watering-head-assembled.jpg" position="left"%}


At this point, it was functionally complete and it went into use at work. However, there was no easy way to secure the part that connects to the water supply via a removable hose connection, and I was worried that it would get broken if it was hanging loose, so I took the chance to overthink the problem and make the most elegant solution I could to securing the setup to the mixer. This required two designs: a clamp that would secure the pipes perpendicularly to the 1/2" bars on top of the mixer, and one that would somehow clamp the inlet end to the side of the mixer. The former took a painfully long time to design because of its complexity and my self-imposed restriction to only use two screws per clamp (pretty reasonable because stainless steel fasteners aren't cheap). After four 3D-printed prototypes and who knows how many hours staring at Fusion, I printed six of them in white PETG (0.25 mm layer height) for installation.


{% include figure.html image="/assets/pipe-clamp-1.jpg" caption="After pressing the nuts into the nut traps, the bottom piece fits tightly onto the rod." position="left"%}


{% include figure.html image="/assets/pipe-clamp-2.jpg" caption="Then, the middle piece dovetails on to the bottom piece." position="left"%}


{% include figure.html image="/assets/pipe-clamp-3.jpg" caption="The pipe can then rest on top of the assembly, and the top piece hooks on and snaps over the pipe." position="left"%}


{% include figure.html image="/assets/pipe-clamp-4.jpg" caption="Install the screws and washers and it'll do its thing." position="left"%}


After finishing this design, I borrowed the tolerances and some design features to make the piece that mounts the inlet end to the side of the mixer. All I had to work with here were some bolts and nuts protruding from the bearing, so I started by designing a piece that would slip over two of the exposed bolts and contour around the bearing housing, securing itself using set screws. After measuring the lateral position and distance of the pipe coming down past the bearing, I added a pair of "arms" with clamps on their ends, very similar to the previous design. The main part could just barely print in one piece on my Prusa i3 because of its length, but printing it at a diagonal on the bed let me squeeze it into the print area. This was printed in the same white PETG with the same settings as before.


{% include figure.html image="/assets/valve-bracket-installed-1.jpg" caption="I designed this to use the same hardware as the clamps, and it has holes/nut traps for four set screws but I ran out of screws and two works just fine." position="left"%}


{% include figure.html image="/assets/valve-bracket-installed-2.jpg" caption="It fits really snug, but I didn't get the contour around the bearing right until the second try" position="left"%}


This was a really fun project and it was a good chance to work on my general design skills and to get comfortable with Fusion, as I have mainly used Solidworks in the past. It was especially helpful to have a reason to practice designing for the purpose of 3D printing, which has similar limitations to other forms of CNC machining, as I plan to use 3D-printing extensively for my main Div III project.
