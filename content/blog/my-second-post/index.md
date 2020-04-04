---
title: My Second Post - Project List
date: "2020-04-04T00:00:00.121Z"
---

Well, I guess to provide some kind of reference for the upcoming posts, 
I thought it would be useful to provide a list of my current projects 
with some background as to what the project is for and where it's likely
to go.  Eventually, each will have a page created so progress can be 
tracked more easily.


## The Light Show
([Github Link](https://github.com/jrrodgers68/lightshow))

My 7 year old son is less than excited about his bed, so I decided to 
add a LED strip to the under side of his bed to put on a light show
before bed time.  The light show controller is connected to my home
automation system running Home Assistant ([Web Link](https://www.home-assistant.io/)).  The controller is made up of 2 parts: an Arduino Mega that runs
the light shows and a Particle Photon that connects to an MQTT broker
that I run for home automation.


## Master Closet Fan Controller
([Github Link](https://github.com/jrrodgers68/MasterClosetFanController))

My house had 2 very tiny closets for the master bedroom (but the room itself is **HUGE**).  In addition, there is a sitting room just off the bedroom that was
basically useless - so we turned that room into a giant master closet.  The
old closets turned into storage rooms.  Unfortunately, the closet have no
airflow and also boarders the outside of the house so they get very cold.  
To address this, I cut a large hole in the wall and mounted a fan to draw
warm air into the closet and attached a vent to the bottom of the door to
allow the air to exit.  I developed a Particle Photon based solution - 
run the fan under 2 approaches - either temperature based OR time based.


## Alone Together 2020

Brandon Satrom ([Twitter Link](https://twitter.com/BrandonSatrom)) streamed
on Twitch ([Web Link](https://twitch.tv)) and created a project to connect
Particle users.  The project involves receiving a public message and 
then responding to it.  I connected the message handler to the light show!
So any time that message comes in, the light show goes on (except before 9am or 
after 9pm!).  Here is a video I made with Noah having the light show start up
with the message coming in (it also lights up the blue led on the redboard) -
([Instagram Link](https://www.instagram.com/p/B-NiUCdp_o7/))


## PC Improvements

My current desktop is new - I build it just after this past Christmas.  I'm 
not fully happy with it at the moment.  Though I'm not a gamer, I've gotten
into the RGB a bit, so I have new RBG strips on the way - the ones included
with the case are a bit annoying.  I also have a new set of faster RAM
coming in late July.


## Harry Potter Magic Wand Spells

We went to Universal Studios and my son was enchanted by the Harry Potter 
spells.  So we spent $60 on a wand and he was able to perform the spells 
at Universal Orlando.  When we got home I looked up how it worked.  The 
end of the wand is basically just a IR reflector and that is picked up
by a camera.  There are a variety of open source projects to replicate 
this at home.  Goal is to get it working and 3D print some wands for 
next Halloween.  There will be a station that you have to perform a 
spell to get your reward.  


## Voice Controlled Train Tracking

In the mornings when I get ready for work, I want to be able to just 
ask a voice controlled system to check the things I need to know in 
the morning: weather forecast and the train status.  NJ Transit has 
a developers program and it requires providing them a fixed IP that 
they whitelist to hit their api endpoints - so will need a hosted VM
someplace that serves as that source for me.


## Tiny ML projects

Machine learning is another area of interest.  I picked up the TinyML 
book from O'Reilly and want to work through various examples using 
some hardware I just got.


## Particle Xenons New Life

I have a collection of about 10 Particle Xenons - which will no longer be 
supported at the end of the year.  Its time to plan ahead and find a new
OS/environment to run on them!


## Shoe Bench

When I find time, I like to work on projects other than electronics as well, 
such as woodworking.  The next project is to build a shoe bench for the 
hallway that leads to the garage.


## Giant Board

I supported Giant Board on CrowdSource and need to get it up and running!  I
was waiting for a FeatherWing with Ethernet and its here so time to figure
out how to bring it to life.


## House Thermostat

The heating upstairs is **very** inconsistent.  The issue is the house has 2
zones but has a *grand entry way* which allows the heat from downstairs to 
go right to the thermostat upstairs - causing it to stop heating.  All the
bedrooms upstairs have exterior walls and so the temperature drops in the
bedrooms while the hallway with the thermostat stays warm.  The goal will 
be to have remote temperature devices in a few rooms and them determine the
HVAC control based on the average room temperatures.


## Noah's Night Light Power Supply

Noah has a laser etched Charmander that lights up via USB (5 volts).  It wil
end up staying on all night without some sort of smarts - so time for 
another project!


## Halloween Mask Improvements

I created a Halloween decoration to scare the kids!  Its a monster mask 
mounted on a wig holder.  The eyes are red leds.  The next improvement
is to add sound.


## Home Assistant Improvements

My current Home Assistant setup needs some work.  I ended up trashing my
zwave network and needed to reset all the nodes.  So I have to go around
and add each of them back into the network.  Unfortunately, I build all
my automations around custom node ids, so each has to be added and properly
named...  *sigh*


## Web Link Management

I use a ton of VMs for everything I do - I only run VirtualBox on my PC, 
everything else is done inside a VM.  This results in stored web links 
in lots of places - running a variety of browsers.  So I want to create 
a simple web link management tool - plus I want an excuse to learn React!


## Hack The Box
([Web Link](https://hackthebox.eu))

I just started working with Hack The Box, need to keep going...


