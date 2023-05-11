# learning
###projectpython
import turtle
t = turtle.Turtle()
# thiết lập màu nền
turtle.bgcolor('light blue')
t.speed(5)
# vẽ nhà
t.pensize(2)
t.pencolor('black')
t.fillcolor('blue')
t.penup()
t.goto(-200,0)
t.pendown()
t.begin_fill()
t.fd(200)
t.rt(90)
t.fd(250)
t.rt(90)
t.fd(200)
t.rt(90)
t.fd(250)
t.end_fill()

# vẽ mái nhà
t.fillcolor('pink')
t.penup()
t.goto(-200,0)
t.pendown()
t.begin_fill()
t.goto(-100,100)
t.home()
t.goto(-200,0)
t.end_fill()

# vẽ mai vòm
t.fillcolor('orange')
t.penup()
t.home()
t.pendown()
t.begin_fill()
t.goto(150,50)
t.goto(50,150)
t.goto(-100,100)
t.home()
t.end_fill()

# vẽ tường 
t.fillcolor('yellow')
t.penup()
t.home()
t.pendown()
t.begin_fill()
t.goto(150,50)
t.goto(150,-200)
t.goto(0,-250)
t.home()
t.end_fill()

# vẽ cửa sổ
t.fillcolor('brown')
t.penup()
t.goto(50,-100)
t.pendown()
t.begin_fill()
t.goto(100,-82)
t.goto(100,-32)
t.goto(50,-50)
t.goto(50,-100)
t.end_fill()

# vẽ cửa nhà
t.fillcolor('green')
t.penup()
t.goto(-125,-250)
t.pendown()
t.begin_fill()
t.goto(-75,-250)
t.goto(-75,-125)
t.goto(-125,-125)
t.goto(-125,-250)
t.end_fill()


# vẽ cái mặt trời
t.fillcolor('yellow')
t.penup()
t.goto(300,300)
t.pendown()
t.begin_fill()
t.circle(50)
t.end_fill()

# vẽ các cạnh dài mặt trời
t.penup()
t.goto(300,300)
t.pendown()
t.goto(300,250)

t.penup()
t.goto(300,400)
t.pendown()
t.goto(300,450)

t.penup()
t.goto(350,350)
t.pendown()
t.goto(400,350)

t.penup()
t.goto(250,350)
t.pendown()
t.goto(200,350)

# vẽ các cạnh ngắn mặt trời

t.penup()
t.goto(300,300)
t.circle(50,45)
t.rt(90)
t.pendown()
t.fd(30)

t.penup()
t.lt(135)
t.goto(350,350)
t.circle(50,45)
t.rt(90)
t.pendown()
t.fd(30)

t.penup()
t.lt(135)
t.goto(300,400)
t.circle(50,45)
t.rt(90)
t.pendown()
t.fd(30)

t.penup()
t.lt(135)
t.goto(250,350)
t.circle(50,45)
t.rt(90)
t.pendown()
t.fd(30)

#vẽ cây

# thân cây
t.fillcolor("brown")
t.penup()
t.goto(375,-200)
t.pendown()
t.begin_fill()
t.goto(425,-200)
t.goto(425,-100)
t.goto(375,-100)
t.goto(375,-200)
t.end_fill()

# vẽ lá
t.fillcolor('green')
t.penup()
t.goto(325,-100)
t.pendown()
t.begin_fill()
t.goto(475,-100)
t.goto(400,0)
t.goto(325,-100)
t.end_fill()


t.penup()
t.fillcolor('green')
t.goto(325,0)
t.pendown()
t.begin_fill()
t.goto(475,0)
t.goto(400,100)
t.goto(325,0)
t.end_fill()

t.penup()
t.fillcolor('green')
t.goto(325,100)
t.pendown()
t.begin_fill()
t.goto(475,100)
t.goto(400,200)
t.goto(325,100)
t.end_fill()

t.penup()
t.home()
turtle.done()
