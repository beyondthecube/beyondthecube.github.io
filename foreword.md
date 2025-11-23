---
layout: default
title: In Place of a Foreword - DAR - an Easy and (Relatively) Fast Method to Solve Any Twisty Puzzle
permalink: /foreword/
toc: true
---

# In Place of a Foreword - DAR - an Easy and (Relatively) Fast Method to Solve Any Twisty Puzzle.md

> *The best way to start learning to solve a Rubik's cube, like solving any other difficult problem, is to get your hands on it and play with it, then you might figure out something important and hopefully how it works.*

## Introduction: Why Are You Reading This?

So, you want to solve the Rubik's cube. Perhaps you've thrown away the tutorial that came with it, preferring the challenge of figuring out the solution by yourself. It's an admirable goal, but this approach can lead to a few problems:

1. You have completely no idea where to even start.

	And that's why you are reading this. This "tutorial" is "spoiler-free". You don't get instructions without telling you why doing so will work, and even when there are instructions, you will probably see why this step makes sense after following the thinking process of previous pages. Instead, *Beyond the Cube* focuses on using questions and visual guides to inspire you to figure out the way to solve the cube all by yourself, using no "algorithms" to memorize and making every step understandable, while teaching important approaches and techniques for general problem-solving.

2. The 3x3x3 Rubik's cube is just one of the most basic puzzles. Many other cubes exist that look far more complicated. If you want to solve these without a tutorial, you might wonder:
	- Do you need to start from scratch each time?
	- Will you have to re-figure everything out, just like when you first tackled the 3x3x3 cube?
	- Wouldn't this become a much more tedious process for each new puzzle, especially larger ones?

<figure>
	<div style="display: flex; gap: 10px;">
		<img src="https://rkocka.hu/image/cache/rkocka/rubik-kocka/rubik-kocka-mastermorphix/shengshou-4x4x4-mastermorphix-cube--31475-600x600.png" alt="Tetrahedron" style="width: 30%; height: auto;">
		<img src="https://ae01.alicdn.com/kf/HTB1afOELpXXXXaaXFXXq6xXFXXXz/Shengshou-Gigaminx-Magic-Cube-Puzzle-Black-and-White-Dodecahedron-5x5-Speed-Cube-Game-Learning-Educational-Cubo.jpg" alt="Dodecahedron" style="width: 30%; height: auto;">
		<img src="https://m.media-amazon.com/images/I/61RoZxnm3KL._AC_SL1500_.jpg" alt="Wierd-cube" style="width: 30%; height: auto;">
	</div>
	<figcaption>How could knowing how to solve the 3x3x3 cube help in solving these puzzles?</figcaption>
</figure>

If you don't want to become a pro at other cubes and just want to learn to solve them, this article is the only thing you need, the second appendix will guide you to generalize the method for solving the 3x3x3 Rubik's cube to almost any other twisty puzzle.

But before diving in, I'd like to show you one of the biggest discoveries in cube theory: the DAR method, a well-known method in the cubing community that is a general solution to *any* twisty puzzle, it is not hard to learn, and there are quite a few puzzles where this method is the fastest one found. Though I would generally avoid using this method as it is somewhat cheating: it takes advantage of a mechanical exploit that almost every type of twisty puzzle has, getting the cube into a special state where shuffling the pieces is a lot easier.

## The DAR Method

To get the 3x3x3 cube into this state, first turn the top layer 45 degrees in either direction.

![U1:2.png](/resources/U1_2.png){: width="50%"}

Then, grab this edge piece in the middle by its sides marked by the red lines and give it a not-so-gentle twist.

![D1.png](/resources/D1.png){: width="50%"}
This piece should come off, and you just got the cube into this special state. You are now able to take all the pieces off the cube and reassemble them in the right order. Thus the name of this method: **Disassemble And Reassemble**.

No, I'm not trying to fool you, *The best way to start learning to solve a Rubik's cube, like solving any other difficult problem, is to get your hands on it and play with it, then you might figure out something important and hopefully how it works*. In the case of the Rubik's cube, taking it apart and putting it back again is a good way to get familiar with the cube, and you might realize that a lot of your assumptions about the cube are wrong.

**Important note**. As I just mentioned, it will be quite hard to solve a puzzle or learn something without trying it yourself. When you are reading this, always have a cube by the side and follow what I'm talking about. When you find something hard to understand, try it a few times on your cube. Now, take your cube apart.

**What does the cube consist of? Is the cube made of colored
stickers?**

After you take the cube apart, you will probably find that the cube consists of "pieces", multiple stickers that can't be further taken apart, at least when you are turning the cube. When you are turning the cube, stickers don't move by themselves, pieces are moved.

**How many types of pieces are there? Are they essentially different?**

Take a look at the pieces, and you'll quickly find out that some pieces have 3 stickers on them while others have only 2. Those with 3 stickers are initially on the corners between 3 centers, and those with 2 on the edges between 2 centers. Then there is also the core that contains the 6 center "pieces".

<figure>
	<div style="display: flex; gap: 10px;">
		<img src="/resources/Pieces.png" alt="Pieces" style="width: 60%; height: auto;">
		<img src="/resources/Core.png" alt="Core" style="width: 30%; height: auto;">
	</div>
	<figcaption>Left: edge piece. Center: corner piece. Right: cube core</figcaption>
</figure>

**Does the inside part of the corner and edge pieces look the same? However you scramble the cube, will a two-colored piece end up on the corner? Try putting back a corner piece into where an edge piece belongs, between two centers, does it fit?**

**Take a look at the core of the cube, will the relative positions of the center pieces ever change when you scramble a cube (without taking the center caps off)? If not, get familiar with the relative position of centers of different colors (what pros call the *color scheme* of the cube), and especially which pairs of center colors are opposite of each other.**

***\*How many types of pieces are in a 6x6x6 cube? How many types of center pieces does it have? What about edges?***

![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=300&amp;pzl=6&amp;sch=wrgwww)

***\*This special case in the 4x4x4 cube is called "edge flip parity" because it looks as if the "edge" is flipped, can you explain why this name is inaccurate? Did you answer the previous question about edges correctly?***

![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=300&amp;pzl=4&amp;fc=wwwwwwwwwwwwwggwrrrrrrrrrrrrrrrrgwwggggggggggggg)

## The R in DAR: Working a Problem Backwards

To put the cube back together:

1. Choose one center on the core and make it face down on the table
2. Put the 4 edge pieces that should be around it into the right places\
	![R2.png](/resources/R2.png){: width="40%"}
3.	Put the 4 corners on the same layer into the right places\
	![R3.png](/resources/R3.png){: width="40%"}
4.	Insert the 4 edges on the middle layer from the top\
	![R4.png](/resources/R4.png){: width="40%"}

You might have doubts about whether a guide on solving a toy puzzle will have any use for real-life problem-solving. This early I already have an example of some of the problem-solving approaches used in this article that can help solve a seemingly completely unrelated problem:

***What is the easiest way to reassemble the top layer?***

Here I'll introduce a problem-solving approach that will be used extensively throughout this guide: **working a problem backwards**.

1. ***How did you take the first piece off the cube? The way I introduced to do that probably didn't take a lot of effort on most cubes, does it hint you which type of piece should be the last to install and how it should be installed?***
2. ***After you took the first piece off, which pieces were the easiest to remove? Does it hint you which piece should be the second-to-last to be installed?***
3. ***Working backward further, find the order to install all pieces and how to install the last one.***

Like some other questions in later chapters, I won't give you the exact solutions as I believe these questions are enough to guide you to find the solution yourself. If you failed to reassemble the top layer after thinking about these questions, the fault is more likely in your cube, you should loosen the top center cap, or maybe even take it off, so that pieces can be installed more easily (remember to re-tighten or reinstall the center cap after you finish).

If you successfully reassembled the cube, I have some good news for you: in my experience, by disassembling and reassembling the cube, you already have as much actual, non-memorized knowledge of the cube as most non-pro cubers.

Now it's time to scramble your cube and start your journey!
