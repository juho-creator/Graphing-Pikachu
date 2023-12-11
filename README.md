# Interactive Pikachu Graph
* This is an interactive graph of pikachu and pokeball floating on water
* Total of 30 equations of 10 different types of functions were used.
<br />
<br />


# Graph Demo
![Pikachu_-_Chrome_2023-05-28_16-11-35_AdobeExpress (1)](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/df81b209-0bf5-4404-8255-aa2323151de5)
<br />
<br />
<br />
<br />
<br />

# How to use the interactive graph
1. Click [Pikachu Graph](https://www.desmos.com/calculator/v8mpye0wof) to access the interactive graph
2. Click on the play button inside each folder to control each component
3. For more details on animation control, refer to [control settings](https://github.com/juho-creator/Interactive-Pikachu-Pokeball-Graph/blob/main/README.md#control-settings)

<br />
<br />
<br />
<br />


# Control Settings
* You can play around with the settings for Pikachu, Pokeball and water. <br />
* The control settings for each component are in the following folders :  **`Pikachu_Control, Pokeball_Control and Water_Control`**
<br />


### Pikachu_Control :
* **P <sub> Horizontal</sub>** : Horizontal position of Pikachu 
* **P <sub> Vertical </sub>** : Vertical position of Pikachu
<br />
<br />


### Pokeball_Control: 
* **B	<sub>Horizontal</sub>** : Horizontal position of four people
* **B <sub>Vertical</sub>** : Vertical position of pokeball
<br />
<br />


### Water_Control :
* **W <sub> Flow</sub>** : Enables water animation<br />
* **W <sub>Amp </sub>** : Wave amplitude<br />
* **W	<sub> freq</sub>** : Frequency of wave <br />
* **W <sub>Level </sub>** : Water level<br />

<br />
<br />
<br />
<br />

# Creation Process

## Pikachu Design

Creating the Pikachu involved a substantial time investment, employing multiple equations to accurately trace each segment.

**Step 1:** The base image of Pikachu was imported into Desmos. <br /><br />

**Step 2:** A parabolic equation was developed with variable constants A, B, and C to control concavity, X and Y positions. <br />
This equation was used to trace specific sections of Pikachu:
$Y = A((X - B)^2) + C$
<br /><br />

**Step 3:** After aligning the graph with the image, unnecessary portions were removed using domain and range adjustments. <br />
![Step 3](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/88e56472-a879-4144-8cb2-e50f300d62f0)
<br /><br />

**Step 4:** If the parabolic equation didn't cover certain sections, other equations were applied <br />
(Ex : Circles, Ellipses, Logs, Exponentials, Cubics, Square roots).<br />
![Step 4](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/848dce22-e0b1-4037-8e9f-9bb35d6382d9)
<br /><br />

**Step 5:** Steps 1 to 4 were iterated to complete the Pikachu image. <br /><br />

**Step 6:** To make Pikachu interactive, slider variables were incorporated into each partial equation, enabling control over Pikachu's horizontal and vertical alignment. <br />
![Step 6](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/f740967f-7dd2-4423-91c6-f995e49a12b5)

This comprehensive process led to the creation of interactive Pikachu , meticulously constructed through a combination of equations and careful adjustments.

<br />
<br />
<br />
<br />

## PokeBall Design

Crafting the PokeBall involved a straightforward procedure employing a horizontal asymptote and two circles.

**Step 1:** The equation template for the circle was established as : $(X-A)^2 + (Y-B)^2 = C^2$. <br /><br />

**Step 2:** The size of the two circles was adjusted. <br />
![Step 2](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/beb67fe5-adab-4f77-96ee-f9a7a85dfbb5)
<br /><br />

**Step 3:** Two distinct horizontal asymptotes were generated, each with specific domains, to form the central lines of the PokeBall. <br />
![Step 3](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/762c90a4-571c-4e8f-b0fa-2b941eb5b2a0)
<br /><br />

**Step 4:** Incorporating two slider variables into each equation facilitated control over the PokeBall's horizontal and vertical positioning.<br />
![Step 4](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cbe51756-feb1-4c6c-8cad-c2208d755d21)
<br /><br />

This streamlined process resulted in the creation of the interactive PokeBall, leveraging equation-based design and dynamic adjustments.

<br />
<br />
<br />
<br />

## Water Design
The creation of the water equation was a relatively straightforward process, employing a sinusoidal equation with an inequality. <br />
However, the challenge emerged in developing various interactive features for the sinusoidal wave.
<br /><br />


**Step 1:** The sinusoidal function was combined with an inequality to generate the effect of a wave-like form filled with colors under the graph, mimicking the appearance of water.<br />
![Step 1](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/cc93cff3-219d-404b-b094-5d4abb404dfa)
<br /><br />

**Step 2:** To enable control over the water waves, four slider variables were introduced.<br />
![Step 2](https://github.com/juho-creator/Graphing-Pikachu/assets/72856990/b03b495f-4305-4717-ab9a-d8a5ae29f076)
<br /><br />
This approach led to the creation of the water effect, utilizing a sinusoidal equation with interactive components for a dynamic visual experience.

<br />
<br />
<br />
<br />


# Graph Components

For each of the components, the graph functions are organized into the following folders:

### 1. Pikachu
Pikachu is composed of the following functions:
* Circles (9)
* Parabola (9)
* Ellipse (2)
* Log (2)
* Exponential (1)
* Cubic (1)
* Square root (1)
<br /><br />

### 2. Pokeball
Pokeball consists of the following functions:
* Circles (2)
* Horizontal asymptote (2)
<br /><br />


### 3. Water
Water is made up of a sinusoidal function.
<br /><br />

In total, 30 equations of 10 different types of functions were utilized in the creation of these graphical components.
 
