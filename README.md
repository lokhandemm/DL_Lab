# Single-Layer Perceptron for Logic Gates 
                       
## 📌 Overview      
This project implements a **Single-Layer Perceptron** to classify binary inputs using a **Step Activation Function**. It is used to simulate basic logic gates (**AND, OR, NOT, NAND, NOR**) and extended with a **Multi-Layer Perceptron (MLP)** to handle **XOR and XNOR**, which are non-linearly separable.  

## 🚀 Implementation  
- A **Single-Layer Perceptron (SLP)** is used for **AND, OR, NOT, NAND, and NOR gates**.
- A **Multi-Layer Perceptron (MLP)** is used for **XOR and XNOR gates**, as they require non-linearity. 
- The model is tested and validated with all binary input combinations. 

## 📊 Truth Table Validation

| Input (X1, X2) | AND | OR  | NAND | NOR | XOR | XNOR |
|---------------|-----|-----|------|-----|-----|------|
| (0,0)        |  0  |  0  |  1   |  1  |  0  |  1   |
| (0,1)        |  0  |  1  |  1   |  0  |  1  |  0   |
| (1,0)        |  0  |  1  |  1   |  0  |  1  |  0   |
| (1,1)        |  1  |  1  |  0   |  0  |  0  |  1   |

 
