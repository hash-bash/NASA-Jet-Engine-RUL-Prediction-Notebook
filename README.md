# NASA Jet Engine Remaining Useful Life (RUL) Prediction Notebook
Prediction of Remaining Useful Life (RUL) of NASA Turbofan Jet Engine using libraries such as Numpy, Matplotlib and Pandas. Prediction is done by training a model using Keras (TensorFlow).

### Data set characteristics:

 - Data set name: NASA Turbojet (FD002)
 - Train trjectories: 260
 - Test trajectories: 259
 - Conditions: SIX
 - Fault Modes: ONE (HPC Degradation)

### The data are provided as a text file with 26 columns of numbers, separated by spaces. Each row is a snapshot of data taken during a single operational cycle, each column is a different variable. The columns correspond to:

- Unit number
- Time, in cycles
- Operational setting 1
- Operational setting 2
- Operational setting 3
- Sensor measurement  1
- Sensor measurement  2
... 
- Sensor measurement  26
