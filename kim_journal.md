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
               
               
               
 def setup():
  size(600, 600)
  background(255)
  strokeWeight(10)
  
def draw():
    stroke(0)
    
def mouseClicked():
    stroke(0)
    rect(100, 100, 400, 400, 50)
    stroke(255, 0, 0) #red, green, blue
    n = random(0,7)
    
    if 2<=n<3: 
        # number one
        circle(300, 300, 50)
    if 3<=n<4: 
        # number two
        circle(200, 200, 50) # top left
        circle(400, 400, 50)
    if 4<=n<5:
        # number three
        circle(300, 300, 50)
        circle(200, 200, 50) # top left
        circle(400, 400, 50)
        
    if 5<=n<6:
        # number four
        circle(200, 400, 50)
        circle(200, 200, 50) # top left
        circle(400, 200, 50)
        circle(400, 400, 50)
    
    if 4<=n<5:
        # number five
        circle(200, 400, 50)
        circle(200, 200, 50)
        circle(400, 200, 50)
        circle(400, 400, 50)
        circle(300, 300, 50)
    
    if 6<=n<7:
        # number 6
        circle(200, 400, 50)
        circle(200, 200, 50)
        circle(200, 300, 50)
        circle(400, 200, 50)
        circle(400, 400, 50)
        circle(400, 300, 50)
        
        
  We made a dice and guessed other people's secret number. We learned how to randomize the dice and also we learned the location of the dots. 
  
  
  
  
  In this class, we practiced connecting the line of breadboard and arduino to turn the light on. 
  I made 4 different versions of turnging the light. 
  
  void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(10, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

