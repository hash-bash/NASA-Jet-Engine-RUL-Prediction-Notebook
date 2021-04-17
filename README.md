# NASA Jet Engine Remaining Useful Life (RUL) Prediction Notebook
Prediction of Remaining Useful Life (RUL) of NASA Turbofan Jet Engine using libraries such as Numpy, Matplotlib and Pandas. Prediction is done by training a model using Keras (TensorFlow).

### Data set characteristics:

  1)  Data set name: NASA Turbojet (FD002)
  2)  Train trjectories: 260
  3)  Test trajectories: 259
  4)  Conditions: SIX 
  5)  Fault Modes: ONE (HPC Degradation)

### The data are provided as a text file with 26 columns of numbers, separated by spaces. Each row is a snapshot of data taken during a single operational cycle, each column is a different variable. The columns correspond to:

  1)  Unit number
  2)  Time, in cycles
  3)  Operational setting 1
  4)  Operational setting 2
  5)  Operational setting 3
  6)  Sensor measurement  1
  7)  Sensor measurement  2
  
  26) Sensor measurement  26
