 Interactive Pikachu Graph
 =============

I created an interactive graph of pikachu and pokeball floating on water using various graphs!
The pikachu, pokeball and water is made interactive to make it even better!

![giphy__1__AdobeExpress](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/be895168-24b0-4cc1-9419-f5ffe3dabc9f)



You can Check it out right here! [Pikachu Graph](https://www.desmos.com/calculator/rzd2rreo3j)

# Creation Process 

## Pikachu
Creating the Pikachu took a very long time because I used so many different equations to trace each parts of Pikachu.

Step 1 : I added a png of Pikachu on desmos. 

Step 2 : Created a parabolic equation with a variable constants A,B, and C each for controlling concavity, X and Y 
position of the graph to match with the picture. The following parabolic equation was used : 'Y = A((X - B)^2) + C'

Step 3 : Once the graph matches with the picture, certain parts were removed using domains and range.

Step 4 : If certain parts weren't covered by parabolic equation, other equations were used(Circles,Ellipse,log, Exponential,Cubic,Square root)

Step 5 : Step 1~4 was repeated to create Pikachu

Step 6 : Two variables were added to each equations for controlling the X&Y position for the horizontal and vertical control of Pikachu


## PokeBall
Creating pokeball was fairly easy because all I needed was a horizontal asymptote and two circles 

Step 1 : Created equation template for the circle '(X-A)^2+(Y-B)^2=C^2'
Step 2 :  Adjusted the size of the two circle 
Step 3 : Created 2 horizontal asymptote, each with different domains for the 2 lines in the middle of the pokeball.
Step 4 : Two slider variables were added to each equations for controlling horizontal and vertical position of the Pokeball.


## Water 
Creating the water equation was easy because I only used sinusoidal equation however coming up with the various interactive features on the sinusoidal wave was difficult. 

Step 1: Sinusoidal function and inequality function was combined to create the affect of having a wave like form filled with blue colors below the graph just like water.

Step 2: 4 variables were added to control the water waves. 



# Control Settings
You can play around with the settings for water, pikachu and the Pokeball. 
The control settings are in the **Water_Control, Pikachu_Control and Pokeball_Control** respectively.


### Pikachu_Control :
P_{Horizontal} : horizontal position of Pikachu
P_{Vertical} : vertical position of Pikachu



### Pokeball_Control: 
B_{Horizontal} : horizontal position of four people
B_{Vertical} : vertical position of pokeball


### Water_Control :
W_{Flow} : Enables water animation
W_{Amp} : Wave amplitude
W_{freq} : Frequency of wave 
W_{Level} : Water level


# Graph components
Graph functions for each components are in the following folders :
### 1.Pikachu
Pikachu is made up of 
  * Circles (9)
  * parabola (9)
  * Ellipse (2)
  * log (2)
  * Exponential (1)
  * Cubic (1)
  * Square root (1) 

### 2.Pokeball
Pokeball is made up of: 
  * Circles (2)
  * Horizontal asymptote (2)

### 3.Water
Water is made up of a sinusoidal function

Total of 30 equations of 10 different types of functions were used. 


