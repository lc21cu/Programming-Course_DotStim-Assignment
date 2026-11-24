# Programming-Course_DotStim-Assignment
DotStim Experiment to be run in Psychopy 

This is a python code written in PsychoPy coder  
(Last altered on psychopy coder v2026.1.3.)

**Requirements:**
1. PsychoPy app  
1a. pandas and matplotlib (available in PsychoPy app)

**Experiment design:**   
This experiment asks participants to select left or right (using arrow keys) to indicate the direction the dots on the screen are moving in. The coherence level (randomness of the background dots) varies between 0.05, 0.1, 0.2, 0.4, and 0.8 with the assumption that the higher coherence, the easier the direction is to detect. The coherence input can be altered on line 69 and can vary between 0-1.

**Data output:**  
The data is saved as an excel file in the same folder as the script, named with the participant number. There is one row per trial.  
Important: The trial does not save is the participant exits before completing the full experiment. 

**Data Analysis / Visualization:**   
Following completion of the experiment, a bar graph shows the percentage correct for both individual directions, separated into coherence levels. The dotted line is at 50% to indicate random chance between left and right.   
Note: the experiment allows participant to select between 10, 50, 100, or 150 trials. At 10 trials, the data shown in the bar graph lacks variation given that each direction is split equally.  
