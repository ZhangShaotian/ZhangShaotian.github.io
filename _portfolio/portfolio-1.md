---
title: "Radio Ray Tracing Optimization via AutoDiff"
excerpt: "Explore the forefront of computational physics in 'Radio Ray Tracing Optimization via AutoDiff'! Dive into how Automatic Differentiation revolutionizes the accuracy and efficiency of modeling radio wave propagation in the ionosphere. Ideal for enthusiasts in computational science and atmospheric studies, this project showcases cutting-edge Python tools like JAX, merging complex mathematics with practical applications. Click to discover how we're reshaping ionospheric modeling!"
collection: portfolio
---

<br/><img src='/images/Raytracing.png'>
### Summary of "Applying Automatic Differentiation to Ray Tracing Problems in Radio" - MEng Design Project Report

#### Author: 
- Shaotian Zhang

#### Advisor: 
- David Hysell

#### Institution: 
- Cornell University, Ithaca

#### Date: 
- Spring, 2023

---

#### Abstract:
- The study focuses on enhancing accuracy in modeling radio wave propagation through the ionosphere using Automatic Differentiation (AD) integrated with a stiff ordinary differential equation solver.

---

#### Key Sections and Highlights:

1. **Introduction:**
   - Importance of the ionosphere in wave propagation and its impact on telecommunications and space exploration.
   - Emphasis on Python and Geometric (Hamiltonian) Optics in analyzing wave propagation.

2. **Ionospheric Fundamentals:**
   - Composition and structure: Mesosphere to Exosphere, high concentration of ions and free electrons.
   - Role in wave propagation: Reflection, refraction, and absorption impacting communication and navigation systems.

3. **Geometric Optics: A Hamiltonian Perspective:**
   - Wave dynamics in various media (fluid, electromagnetic, seismic) described by different sets of partial differential equations (PDEs).
   - Conversion of complex PDEs into a system of ordinary differential equations (ODEs) for simplification.

4. **Variational (Forward) Method for Sensitivity Analysis:**
   - Analyzing the impact of control parameters (e.g., azimuth or elevation of the initial wavevector) on ray trajectories in the ionosphere.
   - Challenges in applying this method beyond Cartesian coordinates and with complex dispersion relations.

5. **Automatic Differentiation:**
   - Overview of AD as a method for evaluating derivatives in computational programs.
   - Benefits include high precision, efficiency, and minimal computational burden.

6. **Implementation in Ionospheric Studies:**
   - 6.1 **Utilization of JAX**: Efficient derivative computation on multiple computational platforms.
   - 6.2 **Employing Diffrax**: Numerical resolution of transformed differential equations.
   - 6.3 **GPU-Accelerated AD with JAX**: Overcoming traditional manual calculation challenges.

7. **Challenges and Breakthroughs:**
   - Optimization of the ionospheric model using actual and simulation data.
   - Encountered difficulties with integrating AD in discrete models (Diffrax solver) and the need for future research.

8. **Conclusion and Future Directions:**
   - Potential of AD tools like JAX in complex computations.
   - Emphasis on further research for reconciling gaps between AD and discrete models.

---

#### References:
- Includes various academic and technical resources related to the project's subject matter.

---

#### Appendices:
- Python code examples and visualizations supporting the study.