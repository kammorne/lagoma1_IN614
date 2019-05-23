---
layout: post
title: "Final Assignment"
date: 2018-11-23
category: Assignments
tags: assignment jekyll
---
# IN614 Final Assignment

## Interactive Map

<iframe frameborder="0" style="height: 810px; overflow:hidden; width: 810px;" src="https://kammorne.github.io/assignments/InteractiveMap.html"></iframe>

## Planning and Execution of My Idea
Originally I had many different ideas for this project, although unfortunately as much as I would have loved to work on some of those ideas, I simply did not have the time, nor the knowledge on how to create my ideas. My original idea was a game like Tetris, however you could only move the pieces in beat with a rhythm, otherwise it drops the piece. Although I had planned on doing that idea originally, once I had opened Adobe Animate to begin working on it, it dawned on me that I didn't have a clue on how to achieve my idea, much less within the timeframe to have my project finished. It was then that I had spoken to Elise about how complex the idea was, and what was expected out of this project. After talking to her, and reviewing the brief for the assignment, I realised that I had a bit more range on some ideas for the project. In the end, I decided on an Interactive Map. Originally I was going to have it display Central Otago Cycling Trails, however I attempted to broaden my idea to the whole of Otago. I began work planning out the design of my map. However, due to time constraints again, I had to eventually scrap the idea of showing the different cycle trails, and instead had it display different information for different towns and cities across the Otago Region.

## Tools Used and How I Used Them
In order to create my program, I used Adobe Animate, and used the HTML5 Canvas as my base for the project. I decided to use Adobe Animate as it was both recommended, and it had all the features I planned to use for this assignment. I also used Adobe Photoshop in order to modify my images, for example, I cropped the Otago region, and made it anywhere outside the Otago Region was a darker colour, in order to convey that my application was meant to display the Otago Region only. For the marker images, I modified them to have the name of the town/city over them in an easy reading font. I also made it that the font had a drop shadow so that it had some contrast against the background image.

Within Adobe Animate, I made use of having different layers for different aspects of my map. Having these aspects in different layers helped a lot when working through my project, as it was extremely handy to lock layers to prevent accidentally selecting the wrong symbol.

![Layers](https://kammorne.github.io/img/finalAssignment/Layers.png "Layers")

![ActionScript](https://kammorne.github.io/img/finalAssignment/ActionScript.png "ActionScript")

When I had finished the functionality of my page, I had attempted to use Javascript to get music to work with my application, however, it did end up causing issues, and eventually I cut the music from my project, even though I would have liked to have had it, since it would have included more "Multimedia" aspects in my application.

In the end, I had multiple different frames within the timeline having it's own Javascript Code, which made the application act more like an actual app, rather than just an animation.

![ActionScriptList](https://kammorne.github.io/img/finalAssignment/ActionScriptList.png "ActionScriptList")

One of the features I found myself using for the city marker, as well as a few times across my timeline, was the ability to label keyframes. This feature made it very easy to work with the Javascript in order to get the timeline to skip to the correct frame when displaying the city marker, by giving it the command "gotoAndStop("label")" instead of having to reference the frame number. Although, with the size of my application, it wasn't too much of an issue. However, if I wished to expand the application further, It would make referencing different keyframes much easier, as I would only need to reference it by name.

![Label](https://kammorne.github.io/img/finalAssignment/Label.png "Label")

In order to increase the Multimedia Experience, I applied sounds to the buttons so that when the user interacts with the application, it has sound feedback. As mentioned earlier, I did want to have music included in my project, However, I was having issues getting it to play all the time, and when I tried to implement a mute button, It didn't affect the music at all. Knowing I was running out of time, I unfortunately had to cut it from the current release.

![Audio](https://kammorne.github.io/img/finalAssignment/Audio.png "Audio")

## Exporting The Project
After consulting Elise about the best format for exporting the application, I ended up exporting it with the HTML5 Canvas. In the previous assignment, I had issues when exporting to HTML5, which included issues with the audio not playing all of the time. After some help from Elise, I understood how to get the sound to work correctly, and got it working in the exported format without issue. When it came to exporting the project, I had to adjust some settings, as every time it did a test export, the quality of the program kept dropping. After some investigating, I found that the colour settings were set to 8-bit, which made the colours looked too muted on the Map, so I ended up boosting the colours to 24-bit. I decided on this option as when I tested it with 32-bit colour, The application would lag out on some of the pages.

![Export](https://kammorne.github.io/img/finalAssignment/Export.png "Export")

I also decided when exporting to have the Javascript included in the HTML file, which kept a cleaner directory for when it came to uploading the project onto Github pages.

## Asset Management

I also made use of the Library again in Adobe Animate, which made it very handy when reusing assets for different parts of my application. I found my use of it improved my workflow, as it made it easy to both reuse, or edit Symbols I had created previously.

![Library](https://kammorne.github.io/img/finalAssignment/Library.png "Library")

The Library was also handy in keeping track of the Symbols I had already created, as I noticed in my First Animation, I was accidentally duplicating Symbols instead of copying them, which was taking up resources in my Application.

One of the best features in Adobe Animate which made my application possible was ActionScript, or in my case, Javascript, since I was working with the HTML5 Canvas. Having Javascript working with my Project was a big step up, as it allowed the user interaction in my project, such as button clicks, moving elements, animating certain elements, and moving to different screens by scrolling through the timeline.

## Design Choices
When it came to design choices, I wanted to keep my design simple. For the marker, I simply had an arrow symbol, and attached a Photoshopped image of the Town/City to the top of the arrow. As mentioned earlier, I photoshopped the images of the Town/City to include the name of the town in an easy-to-read, bold, white font. I also applied a drop-shadow to the text to add some contrast to the text, as the text without the drop-shadow had become hard to read on some of the images, especially when the images were only 100x100px.

When it came to the information sections of the application, I had the information panel appear in a transparent blue/gold. This was to represent the Otago Colours. Originally I had the transparency a lot lower so that it was less visable, however some of the text ended up blending with the background image, which was very noticable in 8-bit colours. I adjusted the transparency of the information panel from 30% to 60%, and found that the text became much easier to read on all of the images.

A small bug I had noticed that would interfere with the user experience was the return button when visiting a Town/City screen. The return button didn't have a collision for the middle of the button until it was in it's hover state, which would only happen if the user hovered over the linework of the button. I had fixed this by simply adding a 10% opacity colour on the inside of the button, which seemed to have fixed the issue.

![ReturnButton](https://kammorne.github.io/img/finalAssignment/ReturnButton.png "ReturnButton")

## Overall Thoughts
I know that if I had more time to work on the project, I would have had a lot more to present. I would have liked to add the functionality to zoom in on certain parts of the map, and if I had gone through with my original idea of displaying different Cycle Trails across the Otago Region, I would have had it so you could have selected those for information, rather than the cities.

I'm also slightly upset that I wasn't able to fully implement music like I had attempted to, however, I know how to implement the music, and get it to play, but I wanted to have the functionality to stop the music, in case a user didn't want to listen to it.

Overall however, I am still happy with how my project turned out, and I still feel like I have learnt a lot with Adobe Animate, especially with using Javascript to make an application with it.
