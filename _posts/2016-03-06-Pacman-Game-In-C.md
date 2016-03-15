---
layout: post
title: "Pacman Game in C"
date: 2016-03-06
author: The Dork Knight Rises
---

So this semester we have a course, Structured Programming Approach (SPA). 
It's basically programming in C language. Since we are the "COMP" class, we get taught by the Principal herself. 
She is a very progress first, marks later kind of person, and I have to admit, I like her approach. 
But then she dropped a project on us. We were divided into groups of three and each group got a different project. 
And as luck would have it, MY group got what is arguably the most complex project of them all:
<br> We had to create a clone of the classic arcade game Pacman in C, within a month.
<br><br>Just to be clear, we are halfway through the introduction to basic C constructs, 
learning about loops and conditionals and just started with the concept of pointers...and we're told to make a friggin game.

<br><br>
<img src="http://i.imgur.com/bi4CRbu.jpg?1" alt-text="Challenge Accepted" width="80%" max-width="305px">
<br><br>

Now, I have a fair bit of experience of experience in Java, and I'm confident I could make a Pacman game in Java.
But working without the concept of objects was new to me, also I had never worked with graphics before, so it was pretty daunting,
what with my teammates assuming that I was a "pro coder" and all. No pressure.

<br><br><b>Week 1: </b><br>
We made a group on WhatsApp and a Github repo for the project. 
That's it, that's all the progress we made, before I went out of town for more than a week.
<br><br><b>Week 2: </b><br>
Returned to Mumbai, fell sick. Got better. Studied for the upcoming Term Test 1 over the weekend.
Teammate worked on drawing basic shapes, getting the shapes to move etc. Finally some progress.
<br><br><b>Week 3: </b><br>
Somehow managed to get through Term Test 1, even after missing so much that had been taught the last 2 weeks.
Tried out different graphics libraries over the weekend, but was told that we had to use the ancient graphic header functions relying on decades old libraries for DOS systems.
We'll be writing code that won't even run on a 32-bit machine without emulating a 16-bit DOS system. Wow.
<br><br><b>Week 4: </b><br>
The deadline is pushed back by a week, cuz of the Term tests. Gotta present the project the next Thursday.
Other teammate also starts working on basic graphics and animations.
They haven't yet figured how to restrict the motion of the Pacman between the walls of the maze, or to make the pellets vanish on being eaten.
We're going out of our minds with tension, but I don't have time to work on the project cuz I'm catching up on all the homework and stuff I missed when out of town.
<br>Friday evening: 
<ul>
<li>08:30 PM: Sit down in front of laptop, start reading up documentation for graphics.h functions.</li>
<li>00:30 AM: Launch Turbo C++, the only program capable of compiling our ancient level of code. Start typing...</li>
<li>05:30 AM: Aaaand, RUN. The maze, the movement of the Pacman, the pellets, the scoring, it's all done. Only the ghosts remaining, then just a lot of polishing needed.</li>
</ul>
<br>Saturday and Sunday: Smoothen things out, fix minor bugs. Added some basics like a Start screen, Pause menu, Game Over screen etc.
<br><br><b>Week 5:</b><br>
<ul><li>Monday: Researched the ghost AI. Apparently they all have different logic 
(<a href="http://gameinternals.com/post/2072558330/understanding-pac-man-ghost-behavior">Interesting article here</a>). 
Coded the most basic one which follows a simple chase algorithm.</li>
<li>Tuesday: Added two more ghosts, one of whose AI logic is completely made up by me :P</li>
<li>Wednesday: Added some music and stuff. We're done here.</li>
<li>Thursday: Presented out game to the class. Everyone loved it, some people came up to me to play it on my laptop. Yaay, successful!</li>
</ul>

<br>So yeah, that's the story of how I made my first game 
<br>(Well, I had a phase around 8 years back when I messed around in CryEngine/UDK/Unity a LOT.
And of course my first complete game was made with GameMaker: a game very similar to Pacman, where a Knight had to rescue a certain Princess from a maze patrolled by the "Meanies". But game engines make things about a 100 times easier than actually typing the code from scratch)

<br>The code for the game is open source under GPLv3 license. Find it here:
<br><a href="https://github.com/TheDorkKnightRises/paC-man">paC-man on GitHub</a>

