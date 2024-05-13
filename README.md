# 6.S966 Final Project Research Paper

## Introduction
This project explores the application of hyperoctahedral symmetries and group equivariant neural networks to classify game states in n-dimensional tic-tac-toe. The motivation stems from the challenge of the exponential parameter space in higher-dimensional games, aiming to use symmetries to reduce computational complexity. The goal is to develop neural models that learn and exploit these symmetries, enhancing prediction accuracy and efficiency, with an end goal of applying sparse tensor libraries for optimization.

## Related Work
- **[Winning strategies in multi-dimensional tic-tac-toe](https://math.stackexchange.com/questions/909786/winning-strategies-in-multidimensional-tic-tac-toe)**: Discusses strategies and mathematical underpinnings for high-dimensional game states.
- **[Symmetry group of a hypercube](https://math.stackexchange.com/questions/1064827/symmetry-group-of-hypercube-in-mathbbr4)**: Provides insights into hypercube geometry, essential for understanding game state symmetries.
- **[Geometric Quantum Machine Learning](https://pennylane.ai/qml/demos/tutorial_geometric_qml/)**: Examines quantum circuits for tic-tac-toe, which inspired the use of equivariant networks without quantum methods.
- **[Hyperdimensional Tic-Tac-Toe by Alyssa Choi](https://momath.org/wp-content/uploads/2021/08/Alyssa-Choi-Tic-Tac-Toe.pdf)**: Theorems and proofs on hyperdimensional tic-tac-toe; used for coding game state checking functions.

## Background
The project utilizes deep learning concepts, particularly group equivariant neural networks, to incorporate symmetries into architecture, enhancing model performance. It also involves advanced group theory and tic-tac-toe mechanics to design appropriate neural architectures.

## Methods
Development involves:
1. **Initialization**: Sets up an n-dimensional tensor as the game board.
2. **Valid Game States**: Checks all possible winning conditions dynamically.
3. **Play the Game**: Implements random and strategic moves to simulate games.
4. **Dataset Generation**: Generates game states for training the neural networks.
5. **Training and Validation**: Uses generated data to train and validate the model performance.

Neural network models are designed to encode the symmetries of hypercube rotations and reflections, leveraging group convolutions to reduce parameter space.

## Experiments and Results
Experiments test model equivariance and performance:
- **Equivariance Testing**: Ensures transformations maintain game state interpretations.
- **Model Performance**: Compares equivariant network outcomes against traditional MLP architectures in terms of accuracy and efficiency.

## Conclusion
The project demonstrates the effectiveness of group equivariant neural networks in handling complex, high-dimensional game state classifications in tic-tac-toe, showing potential for reducing computational demands through symmetry exploitation. Future work will be to refine and expand this repository.

## Acknowledgments
Thank you to the course staff for an interesting class and their guidance throughout the project.

## How to Run the Code
1. **Clone the Repository**: `git clone [https://github.com/zwest808/6.s966-Final-Project]`
2. **Navigate to the Project Directory**: `cd 6.S966_final_project`
4. **Run the Notebook**: `final.ipynb`
