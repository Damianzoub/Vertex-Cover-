# **Solving the Vertex Cover Problem with Quantum Optimization**

## **Project Overview**
This project explores solving the **Vertex Cover** problem—an NP-hard combinatorial optimization challenge—using the **Quantum Approximate Optimization Algorithm (QAOA)**. We compare quantum-based methods with classical brute-force approaches, evaluating performance on various datasets.

##  **Tech Stack & Tools**
- **Programming Language**: Python  
- **Quantum Computing**: PennyLane, D-Wave Cloud, OPENQAOA  
- **Classical Methods**: Brute-force Solver, Local Simulator  
- **Graph Processing**: NetworkX  
- **Optimization Algorithms**: COBYLA, SPSA  

##  **Project Structure**
- **QUBO Formulation**: Converts the Vertex Cover problem into a quadratic optimization problem.
- **Optimization Methods**: Implements **Quantum QAOA**, **Brute-Force**, and **Local Simulations**.
- **Dataset Creation**: Generates random graphs to evaluate performance.
- **Evaluation & Results**: Compares different approaches on computational efficiency and solution accuracy.

##  **Installation & Setup**

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Damianzoub/Verte-Cover.git
   ```
2. **Create a virtual environment (optional but recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

##  **Results & Comparisons**

| Method       | Computation Time | Accuracy | Scalability |
|-------------|-----------------|----------|-------------|
| Brute-Force |  Too slow for large graphs |  Optimal |  Poor |
| Local QAOA  |  Limited by qubits |  Approximate |  Moderate |
| Cloud QAOA  |  Fast |  Approximate |  Scalable |

## 🔗 **References & Documentation**
- [PennyLane API](https://pennylane.ai/documentation)  
- [OpenQAOA Docs](https://openqaoa.entropica.io/docs/)  
- [D-Wave Cloud](https://cloud.dwavesys.com/)  
