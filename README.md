# Wave-Model
This is a personal project of mine created with the intent of simulating a wave based on real-world physics using the Python coding language.

### DFWM_v1.2 (Defined by a Function Wave Model) - 23 Oct 2026
- Implementation of discrete curvature for acceleration calculations.
- Added "Weight Mode" and "Sphere of Influence" variables for force calculations.
- Improved plot designs.
Note: This version of the DFWM was created with assistance from Claude AI for model improvement suggestions and implementation.

### DFWM_v1.1 (Defined by a Function Wave Model) - 16 Oct 2026
- Added Fixed Boundary Points as well as Local Wave Equation Variables such as dx and c.
- Implemented Local Wave Equation Physics.
- Added Simulation Information. Specifically a Model Stability Indicator to assist in the creation of simulation.

### DFWM_v1.0 (Defined by a Function Wave Model) - 14 Oct 2026
Building off of the 2CWM, the next step was to introduce more columns to the wave model to add more complexity. In the process, the columns eventually were replaced with simple points with a defined height, as it made it much easier to produce the figures. Additionally, the initialization of the heights of the points were much more easily created by defining the heights of each initial point by a user selected function (Hence, the name of the Wave Model). Originally, each points acceleration was determined by the 2 closest points but it was later discovered that having the acceleration determined by every point in the simulation created a much more accurate wave. Boundary issue became a new problem in making calculations, as the number of "columns" was now greater than 2 and there were now central points AND edge points. Overall, very happy with how this part of the project has turned out and will be looking to add more to the 1-Dimensional Wave Model before attempting to map out a 2-D wave. Honestly, I don't really like the name but I couldn't think of a good alternative.

### 2CWM ~ Sept 2026
An experimental notebook created around Sept 2026. I wanted to make the most simple physic-based model I could and then expand on the work from this notebook towards future work. I started off with 2 columns or points that were able to influence their acceleration based on the difference in column height. In the end, the program was able to visualize two oscillating columns which when their movement was tracked, showed two distinct waves.

### DFWM_v1.0 (Defined by a Function Wave Model) - 14 Oct 2026
Building off of the 2CWM, the next step was to introduce more columns to the wave model to add more complexity. In the process, the columns eventually were replaced with simple points with a defined height, as it made it much easier to produce the figures. Additionally, the initialization of the heights of the points were much more easily created by defining the heights of each initial point by a user selected function (Hence, the name of the Wave Model). Originally, each points acceleration was determined by the 2 closest points but it was later discovered that having the acceleration determined by every point in the simulation created a much more accurate wave. Boundary issue became a new problem in making calculations, as the number of "columns" was now greater than 2 and there were now central points AND edge points. Overall, very happy with how this part of the project has turned out and will be looking to add more to the 1-Dimensional Wave Model before attempting to map out a 2-D wave. Honestly, I don't really like the name but I couldn't think of a good alternative.

### DFWM_v1.1 (Defined by a Function Wave Model) - 16 Oct 2026
- Added Fixed Boundary Points as well as Local Wave Equation Variables such as dx and c.
- Implemented Local Wave Equation Physics.
- Added Simulation Information. Specifically a Model Stability Indicator to assist in the creation of simulation.

### DFWM_v
