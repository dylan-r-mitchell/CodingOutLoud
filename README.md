# Coding Out Loud - Episode 4

**Visualization**

<img width="436" alt="FinalVisualization" src="https://user-images.githubusercontent.com/97135506/204906849-d58a7eab-a61c-4f2d-a41b-5df4c2a64bc9.png">

**Description of Visualization**

This visualization was created using the ggkeyboard package created by Sharla Gelfand. Data for this visualization was taken from a data set of possible Wordle words created by tabatkins. The first letter of each possible word was taken and counted to determine which letters would be the most common. The 20th, 40th, 60th, and 80th quantiles of the number of occurrences were used to determine which letters would receive what colors. Keys that are not used in Wordle, i.e. any key that's not in the alphabet, were colored with sage green. Keys with occurrences less than or equal to 217 were colored with yellow.  Keys with occurrences between 218 and 429 were colored with sky blue. Keys with occurrences between 430 and 646 were colored with blue. Keys with occurrences between 647 and 882 were colored with crimson. Finally, keys with occurrences greater than 882 were colored with dark red. 

