
import turtle
import random

x = 1
SN = turtle.Screen()
SN.bgcolor("black")
a = turtle.Turtle()
a.speed(200)

i = 0
while x < 256:

    r = random.randint(0,255)
    g = 200
    b = 150
    
    turtle.colormode(255)
    a.pencolor(i,g,b)
    if x<252:
        a.pensize(1)
        a.forward(50 + x)
        a.right(91.5)
       
    x = x+1
    i = (i+1)%255    

turtle.done()
