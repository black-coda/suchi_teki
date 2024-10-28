# suchi-teki: Numerical Analysis Toolkit

**suchi-teki** is a cross-platform mobile application that solves various numerical analysis problems. It features a Flutter-based UI and a Python backend (using FastAPI, numpy, scipy, and sympy) to implement key methods from numerical analysis, including root-finding algorithms, numerical quadrature, and numerical methods for solving ODEs.

## Features

- **Root-Finding Algorithms**: 
  - Newton-Raphson
  - Fixed-Point Iteration
  - Secant Method
  - Regular Falsi
  - Bisection Method
  - Durand-Kerner Method

- **Numerical Quadrature**:
  - Trapezoidal Rule
  - Simpson's Rule
  - Finite Method (PDE)

- **Numerical Methods for ODEs**:
  - Euler’s Method
  - Backward Euler Method
  - Trapezoidal Rule
  - Runge-Kutta Methods
  - Runge-Kutta-Fehlberg Method

## Tech Stack

### Frontend (Flutter)
- **Dart**: For building a cross-platform mobile app.
- **Provider** or **Riverpod**: For state management.
- **http**: To handle communication with the backend (Python FastAPI).
  
### Backend (Python)
- **FastAPI**: A modern, fast web framework for building APIs.
- **Numpy**: For numerical operations.
- **Scipy**: For scientific computing.
- **Sympy**: For symbolic mathematics.
- **Uvicorn**: For running the FastAPI server.
  
### Other Tools
- **Pytest**: For testing the backend algorithms.
- **Matplotlib**: Optional for visualizing the numerical solutions.
- **Docker**: Optional for containerizing the application.

## Getting Started

### Prerequisites

- **Flutter**: [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Python 3.8+**: [Install Python](https://www.python.org/downloads/)

### Backend Setup (Python)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/suchi-teki.git
   cd suchi-teki/backend
   ```

2. Set up environmenet and install dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    pip install -r requirements.txt
    ```
3. Run the FastAPI backend:
    ```bash
    fastapi dev backend/app/main.py
    ```


### Frontend Setup (Flutter)

1. Navigate to working directory
2. Install flutter dependencies
    ```bash
    flutter pub get
    ```
3. Run the App
    ```bash
    flutter run
    ```



This `README.md` gives an overview of the project structure and instructions to set up the backend and frontend.


