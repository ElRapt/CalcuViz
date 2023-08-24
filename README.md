

# CalcuViz: Interactive Calculus with Python

**Disclaimer**: I am not a professional mathematician. CalcuViz is designed as a tool for visualization and understanding. For rigorous mathematical studies, please consult relevant academic sources.

CalcuViz is a Jupyter Notebook-based tool designed to offer an interactive environment for visualizing and understanding various calculus operations. It aims to bridge the gap between theory and its real-world applications.

## Features:

### 1. **Function Plotting**:

- **Theory**: Visual representation of mathematical functions provides insight into their behavior. Given a function \( f(x) \), the plot shows all points \( (x, f(x)) \) in the coordinate plane.
  
- **Example Applications**: 
    - Analyzing revenue vs. cost functions in economics.
    - Observing the trajectory of a projectile in physics.

### 2. **Derivative Operations**:

- **Theory**: The derivative of a function represents its rate of change or the slope of the tangent line at any point. \( f'(x) = \lim_{{h \to 0}} \frac{f(x+h) - f(x)}{h} \)

- **Example Applications**:
    - Determining velocity from a position-time graph.
    - Understanding when a company's profits are increasing or decreasing the fastest.

### 3. **Numerical Differentiation & Integration**:

- **Theory**: Numerical methods offer approximations that can be useful in complex scenarios where symbolic methods are cumbersome. Forward difference: \( f'(x) \approx \frac{f(x+h) - f(x)}{h} \)

- **Example Applications**:
    - Calculating approximate changes in variables in engineering simulations.
    - Evaluating complex integrals in statistics.

### 4. **Visualizing Integrals**:

- **Theory**: Integration represents the area under the curve of a function, providing accumulative quantities. \( \int f(x) dx \)

- **Example Applications**:
    - Finding the total distance traveled using a velocity-time graph.
    - Computing the total energy consumption over a period.

### 5. **Optimization Tasks**:

- **Theory**: Optimization in calculus involves finding maximum or minimum values of functions. Local maxima or minima occur where the derivative is zero (or undefined) and the second derivative changes sign.

- **Example Applications**:
    - Determining the optimal pricing to maximize profit in business.
    - Engineering designs that require optimizing a particular parameter, like maximizing the strength of a beam with a given amount of material.

### 6. **Taylor Series Expansion**:

- **Theory**: The Taylor series provides polynomial approximations of functions about a specific point. The more terms in the series, the closer the approximation is to the original function within a certain range. \( f(x) = f(a) + f'(a)(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \ldots \)

- **Example Applications**:
    - Simplifying complex functions for easier analysis in physics or engineering.
    - Predicting future values of financial instruments using known data.

### 7. **Root Finding**:

- **Theory**: Root finding involves determining the values of \( x \) for which \( f(x) = 0 \). Methods like Newton-Raphson provide iterative approaches to hone in on these root values.

- **Example Applications**:
    - Determining break-even points in business financial models.
    - Solving for equilibrium points in dynamic systems in engineering.

### 8. **Differential Equations**:

- **Theory**: Differential equations involve functions and their derivatives. They represent relationships between varying quantities. Ordinary Differential Equations (ODEs) have one unknown function and partial derivatives.

- **Example Applications**:
    - Modeling the growth of populations in biology.
    - Describing circuit behaviors in electrical engineering based on components like resistors and capacitors.

## How to Use:

### Option 1: Interactive Online Version with Binder

1. Click on the Binder badge: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/YOUR_GITHUB_USERNAME/CalcuViz/main?filepath=CalcuViz_tool.ipynb)
    - This will open the notebook in an interactive environment directly in your browser.
2. Wait for the environment to load and initialize.
3. Interact with the notebook: input functions, select operations, and view the results!

### Option 2: Local Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/CalcuViz.git
    ```
2. Navigate to the repository's directory:
    ```bash
    cd CalcuViz
    ```
3. Set up a virtual environment and install the required packages:
    ```bash
    python -m venv calcuviz-env
    source calcuviz-env/bin/activate  # On Windows, use: .\calcuviz-env\Scripts\activate
    pip install -r requirements.txt
    ```
4. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5. In the opened browser tab, navigate to `CalcuViz_tool.ipynb` and open it.

## Feedback and Contributions:

Your feedback is invaluable! If you have suggestions, encounter bugs, or want to contribute, please [open an issue](https://github.com/YOUR_GITHUB_USERNAME/CalcuViz/issues) or submit a pull request.


