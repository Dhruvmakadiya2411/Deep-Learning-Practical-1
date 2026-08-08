# Practical No. 1

## Exploring Deep Learning Libraries and Performing Basic Tensor Operations Using TensorFlow

### Aim
To familiarize students with popular deep learning libraries and perform basic tensor creation and mathematical operations using TensorFlow.

### Scope
This practical introduces the deep learning software ecosystem and covers the installation of TensorFlow, creation of tensors, basic tensor operations, and comparison of commonly used deep learning libraries.

### Dataset
Not Applicable

### Libraries Used
- TensorFlow
- NumPy

## Practical Tasks

### Part A – Installation
- Install TensorFlow using pip
- Verify TensorFlow installation
- Display TensorFlow version

### Part B – Tensor Creation
- Scalar tensor
- Vector tensor
- Matrix tensor
- Three-dimensional tensor

### Part C – Tensor Operations
- Tensor addition
- Tensor subtraction
- Tensor multiplication (element-wise)
- Matrix multiplication
- Tensor reshaping
- NumPy array to TensorFlow tensor conversion

### Part D – Framework Comparison
Comparison of:
- TensorFlow
- PyTorch
- Keras

## Results and Outcome
This practical demonstrates:
- TensorFlow installation and verification
- Tensor creation (scalar, vector, matrix, and 3-D tensors)
- Basic tensor mathematical operations (addition, subtraction, multiplication)
- Matrix multiplication
- Tensor reshaping
- NumPy-to-TensorFlow conversion
- Comparison of TensorFlow, PyTorch, and Keras

The exact TensorFlow version used can be found by running the "Display the Installed TensorFlow Version" cell in `practical1.ipynb`.

## Framework Comparison

| Feature | TensorFlow | PyTorch | Keras |
|---|---|---|---|
| Developed/Backed By | Google | Meta (Facebook) | Originally independent; now integrated with TensorFlow |
| Main Strength | Production deployment & scalability | Flexibility & dynamic computation graphs | Simplicity & ease of building models |
| Ease of Use | Moderate | Moderate to Easy | Very Easy |
| Typical Applications | Large-scale production systems, mobile/embedded deployment | Research, rapid prototyping | Quick prototyping, teaching, beginner-friendly projects |
| Advantages | Strong deployment tools, large community, cross-platform support | Pythonic syntax, easy debugging, strong research adoption | High-level, readable API, fast model building, runs on top of TensorFlow |

## Insights
- TensorFlow provides tools for tensor-based computation.
- Tensors can represent scalar, vector, matrix, and higher-dimensional data.
- Tensor operations form the computational foundation of deep-learning workflows.
- TensorFlow, PyTorch, and Keras have different strengths and use cases.

## Repository Structure
```
Deep-learning-Practical-1/
├── practical1.ipynb
├── README.md
└── requirements.txt
```

## How to Run
```bash
pip install -r requirements.txt
```

Then open `practical1.ipynb` and run all cells to verify that all outputs are displayed.

## Author
**Name:** Dhruv Makadiya
**Email:** dhruvmakadiya800@gmail.com
**Course:** B.Tech – Deep Learning Practical
