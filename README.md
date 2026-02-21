# turtle01

turtle01.py
from turtle import *
shape("turtle")
forward(150)
done()

turtle02.py
from turtle import *
shape("turtle")
for i in range(4):
    forward(100)
    left(90)
done()

turtle03.py
from turtle import *
shape("turtle")
col = ["orange", "limegreen", "gold", "plum", "tomato"]
for i in range(5):
    color(col[i])
    forward(200)
    left(144)
done()

turtle04.py
from turtle import *
shape("turtle")
col = ["orange", "limegreen", "gold", "plum", "tomato"]
for i in range(5):
    color(col[i])
    circle(100)
    left(72)
done()
