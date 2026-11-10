# Jennifer Chang
jtc006@ucsd.edu

**Section:** D06
**Mentor:** Duncan Watson-Parris

**What is the most interesting topic covered in your domain this quarter?**
I personally think the most interesting topic I’ve covered in my domain this quarter is implementing an ocean and seeing how the addition of a slab ocean impacts temperatures and climate over time. Before adding the slab ocean, the atmosphere in our model was running over a fixed sea surface temperature, which meant it could never really respond to the forcing we applied. Adding even a simple slab ocean (simply a bucket of water) with a heat capacity and a Q-flux lets the surface warm in response to CO₂, and we were actually start to see the atmosphere drift toward a new equilibrium rather than just staying around a prescribed one. It definitely made the model feel more realistic

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
A potential investigation I would like to pursue for my Quarter 2 Project is looking at how climate change affects specific regions within the world and events such as monsoons and rainfall. In addition to this, I think it would be really interesting to see how El Niño ties into the data as well. This is especially interesting because the El Niño we are currently facing is the strongest on record, so it would be valuable to see patterns and trends over time, both historically and across regions. 

**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**
A potential change I’d like to make to the approach taken in my current Quarter 1 Project is to spend more time understanding the in-depth details of tasks from my teammates. A lot of the time, we tend to divide up most of the work, and while I do understand at a general level what their tasks do and the intention behind them, I would like to be more mindful of understanding exactly why they chose to write the code the way they did. For example, there were several times when I was handed a script — like the abrupt-CO₂ branching code or a teammate’s pattern-scaling implementation — and I understood what it produced, but I didn’t fully understand the design choices behind it until much later. Slowing down to walk through each other’s code together would make it easier to catch bugs and would give me a deeper understanding of the full pipeline rather than just the slice I personally worked on.

**What other techniques would you be interested in using in your project?**
Along the lines of what I thought was really interesting, I would like to try implementing a more realistic ocean model that takes into account not only surface currents but the deep ocean as well, and see how that changes what we see. The slab ocean we used responds quickly because it only represents the top mixed layer, so it misses the slow adjustment of the deeper ocean that actually sets the long-timescale climate response. Coupling to even a simple multi-layer or dynamical ocean would let me explore phenomena like ENSO, overturning circulation, and the lag between forcing and warming, which can’t really be captured in a slab setup. 
