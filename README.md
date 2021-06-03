# RubberBandLauncher

Asish and Dylan

In this we are making a rubber band laucher with a servo. The servo is activated by a button. When it pressed down on the servo should rotate lauching the rubber band.

# Week #3

Some progress I made in CAD this week is getting all the materials fastened onto the handgun. I put on all the nuts and screws.
One obstacle i had to overcome was making the holes for the materials. I had to make sure they were the right size and in the correct place.

# Week #4 

The project is going pretty good so far. I think the project is well the way it is. 
When I return from spring break, the first thing im going to do is start lazer cutting.

## Psuedo Code

  // first thing is to read both buttons

// use IF statements to determine if a button is being pressed
  
// IF first button is pressed, go clockwise (use button toggle code)
    // IF second button is pressed, go counter clockwise, (use button toggle code)

// if neither button is being pressed, servo should not be moving 
//finally, make sure to serial print the button values and servo value, at the end of void loop
}
 ```C++
const int BUTTON1 = 2;
const int BUTTON2 = 4;

int BUTTONstate1 = 0;
int BUTTONstate2 = 0;

void setup()
{
  pinMode(BUTTON1, INPUT);
  pinMode(BUTTON2, INPUT);
}

void loop()
{
  BUTTONstate1 = digitalRead(BUTTON1);
  BUTTONstate2 = digitalRead(BUTTON2);
}

```

## Circuit Diagram

## Materials 

- 3d printed shell and acrylic glass for the launcher
- two buttons and a switch for the main functions
- a battery and a ardunio board
- nuts and screws


## Pictures/Videos

no picture or videos

## Problems

There was a lot of problems with our projects. Few things that we had trouble with were one of the nuts being stuck in one of the buttons. The screws not being the right size for the hole of the battery holder. Not having the hole for the power source for the ardunio. We could hae avoided this problem if we checked the final desing in onshape before printing. 


## Onshape link
[link](https://cvilleschools.onshape.com/documents/4cffe182c217e96074413ad5/w/d79c45854d2593d63b4d233f/e/66427e71002e2745e77f0d53)
