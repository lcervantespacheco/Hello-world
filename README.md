#Name:  Lilian Cervantes Pacheco
#Email: lcervantespacheco@gmail.com

import turtle
tess = turtle.Turtle()
commands = input ("Please enter a command string: ")

for ch in commands:
    if ch == 'F':
      tess.forward(50)
  elif ch == 'L':
      tess.left(90)
  elif ch == 'R':
      tess.right(90)
  elif c == '^':
      tess.penup(90)
  elif ch == 'v':
      tess.pendown()
  elif ch == 'r':
      tess.color("red")
  elif ch == 'g':
      tess.color("green")
  elif ch == 'b':
      tess.color(blue)
  else:
      print"Error: do not know the command:", ch)
      
print ("See graphics window for your image")    
  
