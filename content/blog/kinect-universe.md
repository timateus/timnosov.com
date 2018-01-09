+++
title = "Exploring the Universe with Gesture Based UI"
description = ""
tags = [
]
categories = [
]
date = "2017-10-17T23:29:28-07:00"

+++

Controlling a computer with gestures is a mind-blowing and perspective-shifting experience. The idea existed since forever ago (i.e Minority Report) and attempts to bring it to masses (Kinect) have been made but gesture control is still far from being ubiquitous, I, for example, have never tried it, until a few days ago.

WorldWide Telescope is an open-source application which provides an interactive way to explore the universe. [Jonathan Fay](https://en.wikipedia.org/wiki/Jonathan_Fay) has build a Kinect interface to navigate Worldwide Telescope:


{{< youtube 1-tMp4WkQjA >}}


[Lab212](http://lab212.org/) have built an art installation using Worldwide Telescope and Kinect to simulate the experience of swinging through space on a swing:

{{< youtube 5Kj_AGNJsL4 >}}

These experiments inspired us to recreate them for the purpose of education and outreach for the [SFU Satellite Design Team](http://sfusat.com/). Harrison Handley was the mind behind the idea and the driving force for the project.

We have decided to substitute Worldwide Telescope with [100,000 Stars Chrome Experiment](http://stars.chromeexperiments.com/) developed by Google’s [Data Arts Team](https://www.html5rocks.com/en/tutorials/casestudies/100000stars/). 100,000 Stars is a fantastic visualization of the Milky Way Galaxy and we chose it over Worldwide Telescope, due to the fact that it was easier to navigate, simpler to understand and simpler to control with Kinect. (Harrison is still very keen on implementing a Worldwide telescope version though.)

Harrison implemented a Kinect interface and came up with a control scheme: hands held together — zooming in, hands wider than elbows — zooming out, making a fist and moving it — to simulating a mouse click and drag.

We demoed this at [Science Rendezvous](http://www.sciencerendezvous.ca/) — Canada’s biggest science fair as a part of the SFU Satellite Design Team’s booth. Our visitors were mostly elementary school children and their parents and also some university-level students. The result was incredible:

* Kids and adults alike were mind-blown by the idea of waving hands to control a computer
* 100,000 Star Experiment with its stunning graphics and a simple control scheme proved to be an excellent way to explore the universe, be fascinated by its size and complexity and be curious to learn more
* Kinect with its cool stick-figure visualization of bodies was a fantastic learning tool — kids and adults were curious about sensors and algorithms and coding languages

What was a true validation of the value of the demo was that many bugs in our demo didn’t drive anyone away or made anyone bored, on the contrary, whenever an issue arose (for example sudden poor gesture recognition), kids wanted to find a way to solve it!

This project turned out to be a fantastic way to unleash creativity and foster curiosity and it was an excellent science, art and technology demonstration.

## Resources

* [Another simple web-based demo to explore space using Kinect](http://stuffin.space/)

* [Worldwide Telescope’s Github](https://github.com/WorldWideTelescope)

* [JS library for interfacing with Kinect](http://depthjs.media.mit.edu/)

