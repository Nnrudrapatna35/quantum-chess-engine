# quantum_chess
Quantum Final Project

In this project, the team created a classical-quantum hybrid engine which can find the queen moves which result in checkmate (in the case of a 4x4 reduced chessboard, with mate in one puzzles). The primary quantum computing aspect of the project involves an implementation of Grover's Algorithm with at most 16 qubits. The algorithm was used to determine all possible permutations of the black king and white king for which the black king would be in checkmate given a specific queen positioning. Then, the queen move(s) which lead to checkmate were found by comparing with the list of all legal queen moves given the initial configuration of the board.
