# feladat

import turtle
 
t = turtle.Turtle()
t.pensize(3) 
firstRowColors = ["blue", "black", "red"] 
for i in range(3):
 t.penup()
 t.pencolor(firstRowColors[i])
 t.goto(i*110, 0)
 t.pendown()
 t.circle(80)
 
secondRowColors = ["", "yellow", "", "green"]
for i in range(1, 4, 2):
 t.penup()
 t.pencolor(secondRowColors[i])
 t.goto(i*55, -50)
 t.pendown()
 t.circle(80)
 
