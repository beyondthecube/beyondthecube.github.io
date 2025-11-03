---
layout: default
title: 2. Where Should I Start?
permalink: /chapter-2/
toc: true
---

# 2. Where Should I Start?

> *For every step you plan, you should try to make future steps not so difficult, often by leaving more degrees of freedom after each step, the best step is usually not the most obvious one*

Knowing that solving a face doesn't solve anything, naturally, you may be thinking:\
***Is solving a layer, meaning not just solving a face but also putting all pieces on that face in the right order, a good way to start solving the cube?***

<figure>
	<img src="https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=gggggggggrrrdrddddyyydydddd">
	<figcaption>A cube with a layer solved</figcaption>
</figure>

In fact, a lot of tutorials online (and probably the one that came with your cube) teach a method that solves the cube one layer at a time. I first learned to solve the cube using this method as well, but as my experience grew, I stopped appreciating this method as I realized that this seemingly logical approach actually has a flaw.

**Are there other criteria for a good "first step candidate" apart from actually solving something?**

One obvious criterion is that the first step itself shouldn't be too difficult, as if you are often stuck on the first step you won't get the chance to solve more of the cube.

The second criterion is important in all kinds of problem-solving: ***when you are planning steps to solve a problem, especially the first steps, for every step you plan, you should try to make future steps not so difficult, often by leaving more degrees of freedom after each step, the best step is usually not the most obvious one***.

***Can you explain why solving all edges first or solving the "T" in the previous chapter aren't good ideas for a first step?***

**Solving a layer isn't difficult, but how easy will future progress be if you solve a layer?**

Look again at this cube with a layer solved:

![](https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=gggggggggrrrdrddddyyydydddd&amp;arw=F0F2-green-s13,R0R2-green-s13,F6F8-green-s13,R6R8-green-s13,U0U6-red-s13,F0F6-red-s13,U0U2-red-s13,R2R8-red-s13,U2U8-red-s13,F2F8-red-s13,U6U8-red-s13,R0R6-red-s13)

As you can see from this diagram, only 2 of the 4 outer layers marked in green can be turned without breaking the solved layer, any turns on the other 4 layers marked in red will destroy your previous progress.

**How much can you do with these 2 free layers?**

Imagine turning these 2 layers a bit and you'll realize: nothing. Since the 2 layers are parallel, meaning they don't intersect, you can't move any piece from one layer onto the other, and thus you can't shuffle around pieces on one layer.

**Wait, then how are there tutorials that solve the cube layer by layer?**

These tutorials use special "algorithms", sequences of moves that you need to memorize, to do things like inserting edges into the second layer and shuffling pieces around on the last layer. All these algorithms break up your previous progress and restore them while solving more pieces. Some (or most) of these algorithms are quite unintuitive and difficult to figure out by yourself. Though after building enough knowledge in the later chapters, you will understand most of them when I explain them in the second appendix. However, most of them only become obvious once you have already seen the solution.

**What about solving all the corners first? That leaves a lot of middle layers free to move, and if we only care about keeping the 4 bottom corners and the 4 top corners together respectively, the top and bottom layers are also free, that's a lot of freedom to move the pieces, would it be a good way to solve the cube?**

Solving the corners first is one of the earliest discovered methods to solve the Rubik's cube, it satisfies the second criterion quite well, but it fails on the first one: try solving all the corners, and you will realize that it's not as simple as you expected.

Why is it difficult? When you solve a face or a layer, you have enough room to store the needed piece (say on another layer), before aligning everything and moving them to the correct spot, but if you want to solve all corners, you are solving all pieces of one type, and that means there is no way to store the last few corners in another spot before inserting them in the right way.

Think about which one is easier: swapping 2 corners on the first layer while allowed to break up the other 2 layers, or swapping 2 corners without breaking anything else on a 2x2x2 cube, which is equivalent to all corners on the 3x3x3 cube.

<figure>
	<dif style="display: flex; gap: 10px">
		<img src="https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=3&amp;fc=gggggggggryoddddddooydddddd&amp;arw=U2U8-yellow,U8U2-yellow" style="width: 30%; height: auto;">
		<img src="https://visualcube.api.cubing.net/visualcube.php?fmt=svg&amp;size=200&amp;pzl=2&amp;fc=ggggywoowoww&amp;arw=U1U3-yellow,U3U1-yellow" style="width: 30%; height: auto;">
	</dif>
	<figcaption>Which one is easier?</figcaption>
</figure>

As I mentioned before, the best step is usually not the most obvious one. To find the best first step, I'm going to introduce another problem-solving approach, probably the most important one in the whole article: **blockbuilding**, and it's not just about building blocks.
