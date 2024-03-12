# PINN_Neural_Networks-PDE_Solvers
Physics-Informed Neural Networks (PINN) for Solving Differential Equations

Overview:
This project explores the capabilities of Physics-Informed Neural Networks (PINN) in solving a variety of differential equations, particularly Partial Differential Equations (PDEs). The project is divided into three main parts, each focusing on a different type of differential equation and inverse problems, utilizing specific techniques to achieve accurate and efficient solutions.

Part 1: Volterra Equation and Implicit Differential Equation (IDE)
In the initial phase of the project, we tackle the Volterra equation and an Integro-Differential Equation (IDE) using PINNs. Employing hard constraints and a feedforward neural network architecture, we demonstrate the effectiveness of PINNs in solving these types of equations with high precision.
![Screenshot 2024-03-12 alle 20 07 45](https://github.com/Davide-Ettori/PINN_Neural_Networks-PDE_Solvers/assets/52358285/a427e64f-a7c7-4511-aa08-ae0735627e64)

Part 2: Kirchhoff's Equation for RLC Circuits (Inverse Problem)
Moving forward, we delve into the realm of inverse problems by addressing Kirchhoff's equation for RLC circuits. In this phase, the PINN learns both the solution to the equation and the capacitance of the capacitor simultaneously. Leveraging a Residual Network (ResNet), we showcase how PINNs can effectively handle inverse problems, offering solutions with high precision and robustness.
![Screenshot 2024-03-12 alle 20 07 45](https://github.com/Davide-Ettori/PINN_Neural_Networks-PDE_Solvers/assets/52358285/d3dd4a98-b17c-452f-af3f-916f362f0eef)

![Screenshot 2024-03-12 alle 20 07 51](https://github.com/Davide-Ettori/PINN_Neural_Networks-PDE_Solvers/assets/52358285/8f12cc5d-53c4-47e3-9b47-61f0684af87a)


Part 3: Burgers' Equation for Viscous Fluids
The final segment of the project focuses on Burgers' equation, a complex, nonlinear partial differential equation governing viscous fluid flow in a tube. Here, we employ the Residual Adaptive Refinement (RAR) sampling technique to capture the impulses within the central region of the fluid tube. By tackling this challenging problem, we demonstrate the versatility and adaptability of PINNs in handling complex fluid dynamics scenarios.
![Screenshot 2024-03-12 alle 20 08 06](https://github.com/Davide-Ettori/PINN_Neural_Networks-PDE_Solvers/assets/52358285/ee2582f0-4820-4869-b383-513c8ce660e5)
![Screenshot 2024-03-12 alle 20 08 32](https://github.com/Davide-Ettori/PINN_Neural_Networks-PDE_Solvers/assets/52358285/c121afdc-caa7-47d3-806b-5ce608deacbc)


Conclusion:
Through this project, we showcase the power of PINNs in looking at a wide range of differential equations encountered in various scientific and engineering domains. By combining neural networks with physical principles, we pave the way for innovative solutions to complex problems, offering new insights and possibilities in the field of computational physics and engineering.
