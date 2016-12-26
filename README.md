#Cellular Automaton Music Generator

This Javascript Music webapp uses a [1 dimensional Cellular Automaton](http://mathworld.wolfram.com/ElementaryCellularAutomaton.html) to produce piano music. 
The generator concept is simple. Each generation is mapped onto a keyboard wherein each live cell represents a played piano note. Thus each generation thus will correspond to a single chord, and the succession of multiple generations will represent a sequence of chords.
It's easier to explain by showing than it is by telling:
##[Try it out!](http://students.washington.edu/abemill/CA/)


I built this website using the [p5js Javascript library](https://p5js.org/). This made it a smooth transition when I wanted to port important parts from my 'proof of concept version' that was built in processing, but it also has created some incredibly frustrating issues. 
I will be the first to admit that I haven't been able to tackle the issues born from how I implemented p5js in the best possible way (looking at the render-glitch-fix checkbox). I also managed to make the UI seem as though it was styled by a Caveman. In my defense, this was the first website I've made, and essentially my first real programming project. 

Since finsishing the Music Generator I have gotten a much stronger grasp on web technologies like HTML/CSS/Javascript; The project is definitely due for a complete rebuild from the ground up, and p5js need not be apart of it.