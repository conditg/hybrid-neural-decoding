# Quantum Hybrid Neural Decoding

### In this project, the brain signals from a monkey are decoded by an LSTM with Variational Quantum Circuits. These results are compared against a classical LSTM to show that Quantum ML may be able to handle higher learning rates and learn more in initial epochs than the classical benchmark.

# Key Files: 

1. High-level Overview of Problem Statement & Findings --> [Quantum-Hybrid-Neural-Decoding-Overview.pdf](https://docs.google.com/presentation/d/1hoGrlTZ9uWxV6_UNjgkVMt5lCf7xixEoYJniV4pD-Ns/edit?usp=sharing)
2. Main Notebook with walkthrough and visuals --> [Neural-Decoding.ipynb](./Neural-Decoding.ipynb)
3. Time Series Model Code including the QLSTM Cell --> [TSModels.py](./TSModels.py)

# Main Results

The faster learning noted below can be attributed to a higher learning rate. When the Classical Model was trained with a comparably high learning rate, the loss was erratic and the model did not consistently converge - examples can be found in the Overview pdf. 

![Loss plot](images/loss.png)
