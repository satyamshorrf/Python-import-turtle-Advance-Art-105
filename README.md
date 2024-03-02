# Python-import-turtle-Advance-Art-105
Create python use import turtle graphics code
from turtle import *
from time import sleep 

bgcolor("black")
t = ["orange", "red", "green"]
for index, t in enumerate(t):
    t.speed(0)
    t.color("white")
    #i.shape("circle")
    t.shapesize(0.5)
    t.width(5)
    t.penup()
    t.seth(90)
    t.forward(230)
    t.seth(-180)
    t.pendown()

t[0].penup() 
delay(0)
speed(0)
hideturtle()
sleep(1)

for i in colors:
    color(i)
    for i in range(360):
        t[0].forward(x)
        t[0].left(1)
        penup()
        goto(t[0].pos())
        pendown()
        t[1].forward(2*x)
        t[1].left(2)
        goto(t[1].pos())
done()        
