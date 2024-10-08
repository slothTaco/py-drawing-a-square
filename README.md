# py-drawing-a-square

The second line

for side in range(4):

is saying we want to repeat some code four times.

After that come the lines of code we want repeated – the body of the loop. We need some way of marking off how far the loop body extends, and in Python we use indentation for this. We shift the lines forming the loop body further to the right by four spaces, and Python will then know the indented lines are the loop body.

Although the spaces are not normally visible (except by their effect on the spacing of course), below we’ve shown them as discs, to help make it clear what we mean.

from turtle import *
for side in range(4):
••••forward(100)
••••left(90)
