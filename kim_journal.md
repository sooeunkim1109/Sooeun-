# This is the journal for comp sci

1. What did we do? 
Today we created
```.py 
x = 0 
def setup():
  size(1000, 1000)
  background(255)
  textAlign(CENTER, CENTER)
def draw():
    print("")
def mouseClicked(): 
    x = mouseX
    y = mouseY
    z = random(10,100)
    myred = random(0,250)
    myblue = random(0,255)
    mygreen = random(0,255)
    fill(myred, mygreen, myblue)
    
    circle(x, y, z)
    fill(0)
    textSize(26/1); 
    text("S&K",x,y)
    
    
    print(x, y, z)
 ```
    
    
    2. What did we learn? 
    --> We learn how to make circles as the way we want circle to appear. We created many versions of coding to make circles. 
    
    
    Homework : 1. Add lines from the middle of the window to each circle 
               2. Add lines from circle to circle
