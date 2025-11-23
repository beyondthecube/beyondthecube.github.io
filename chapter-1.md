---
layout: default
title: 1. What Exactly is "Solving" Something?
permalink: /chapter-1/
toc: true
---

# 1. What Exactly is "Solving" Something?

> *Remember, stickers don't move independently, they move together as pieces!*

***You might have attempted to solve a face before, do you think it is good as a first step in solving the entire cube?***

To answer this question, we need to find a way to judge how much the cube is solved after doing something.

**You probably used to consider the "solved state" as making each face have stickers of only 1 color. This description is inaccurate, using knowledge from the previous chapter, can you describe what exactly needs to be done to solve the Rubik's cube?**

*Remember, stickers don't move independently, they move together as pieces!* You don't solve all the stickers onto the right faces, instead, you need to solve all the pieces into the right places.

**What does it mean for a piece in the cube to be solved?**\ If a piece is solved, it shouldn't change its position compared to when the whole cube is solved. Using the way to understand the "solved state" in the previous question, a solved piece should be between the correct centers and oriented correctly. For example, the white-green-red corner, if solved, should be in the corner between the white, green, and red centers, oriented so that the white sticker on the corner is on the same face as the white center. Here are some examples:

- A solved corner piece:\
![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=ddddwdddwrdddrddddddgdgdddd)
- A solved edge piece:\
![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=ddddydddddddooddddddddggddd)
- A corner piece with one sticker on the right face, but not between the correct centers, thus not solved:\
![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=ddddwdddwgdddrddddddodgdddd)
- An edge piece between the correct centers, but oriented incorrectly, thus not solved:\
![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=ddddyoddddyddoddddddddgdddd)

*Now look at this example of a possible cube state after solving a face, how many pieces that you can see are solved on this cube?*\
![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=gggggggggyrrbrbrbrrworyybob)

Taking a quick look, the only piece that you can be sure is solved is the green-red edge, already between the correct centers. Doing a bit of deduction, the corner piece to the right of the green-red edge must be the white-green-red corner (as the other corner with green and red stickers, the yellow-red-green corner, has the green sticker to the right of red), and since the white center should be opposite of the yellow center, that corner is between the correct centers and thus solved. No other piece is guaranteed solved.

***My last sentence is actually wrong, there is another piece on this cube that is guaranteed solved, but it takes a lot more reasoning to figure out. Can you find that piece?***

If you figured out the problem above without taking a long time, you already have a great understanding of the cube. If you didn't, it's not very important, what I want to say is that even if there are 3 pieces solved, they are solved by chance as I wasn't actively trying to put these pieces in the correct spots, I was just putting them on the green face, and they happened to line up correctly.

**You wouldn't want a method to solve the cube that solves pieces by chance, what would be some candidate "first steps" to solve the Rubik's cube where you actually try to solve some pieces?**

This question doesn't have a "correct" answer until the next chapter, there are tons of options to choose from, such as solving all corners, all edges, an outer layer, a middle layer, or even this T shape in the image below.

<figure>
	<img src="https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=ddddwddwwgddggggdddoodoodoo">
	<figcaption>Why is solving this “T” not a good idea as a first step?</figcaption>
</figure>
