# quantum-password-search
# Search using Grover’s Algorithm

This project demonstrates how Grover’s Algorithm can accelerate brute-force search compared to classical methods, using 2-bit and 4-bit password examples as proof-of-concept implementations.

However, beyond demonstration, the project extends into quantum security analysis.

Modern cybersecurity relies on computational hardness assumptions. Classical symmetric security depends on the infeasibility of exhaustive key search (O(2ⁿ)).
Quantum algorithms such as Grover reduce this complexity to O(2ⁿᐟ²).

This effectively reduces symmetric key strength from n bits to n/2 bits.

To address this, we built a quantum risk modeling framework to:

Evaluate entropy degradation under quantum adversaries

Compare classical vs quantum search complexity

Estimate future cryptographic break timelines

Provide quantum-risk forecasting for real-world systems

🎯 Objectives

Demonstrate classical brute-force search complexity

Implement Grover’s Algorithm for 2-bit and 4-bit passwords

Compare classical attempts vs quantum iterations

Model entropy degradation under quantum attack

Analyze effective security reduction in symmetric cryptography

Classical security assumes exponential brute-force cost (2ⁿ).

Grover reduces search complexity to O(2ⁿᐟ²)

A 128-bit key provides only 64-bit effective security against a quantum adversary.

Entropy is effectively reduced by half.

This shifts the problem from “faster search” to:

Evaluating password entropy under quantum adversaries.

📊 What This Project Demonstrates
✅ Classical Search

Worst-case attempts: 2ⁿ

Exponential scaling

✅ Quantum Search (Grover)

Required iterations ≈ √(2ⁿ)

Quadratic speedup

Reduced effective security margin

✅ Security Modeling

Entropy degradation analysis

Scaling comparison for larger key sizes

Future vulnerability forecasting

⚙️ Technologies Used

Python 3.9+
Qiskit
Qiskit Aer
NumPy
Matplotlib
Jupyter Notebook
