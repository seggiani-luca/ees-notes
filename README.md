# Electronics for Embedded Systems notes
Notes from my Electronics for Embedded Systems class.

Some extra work was done:
- `homework/` contains some homework given in the course slides (do a bit of digging in my website to figure out which). I try to use LTSPICE as it gives a quick SPICE representation of the circuits and also allows for easy simulation;
- `circuits/` contains some circuits (also in LTSPICE). Most are miscellaneous circuits related to the course;
- `circuits/lib` contains a hierarchical set of components to use to build digital circuits (in LTSPICE) (the main target would be something like an ALU or a datapath);
- `circuits/interactive` contains some stuff i built with [Falstad's](https://www.falstad.com/circuit/circuitjs.html) circuit simulator (used instead of LTSPICE because it allows me to click around and see results in real time).

It would eventually be really cool to model a switch-level package to simulate simple CMOS and pass-gate circuits (something like [this](https://seggiani-luca.github.io/logic-sim/) but closer to analog).
I'll play around with the idea, though for now it seems way bigger than what the course entails.

