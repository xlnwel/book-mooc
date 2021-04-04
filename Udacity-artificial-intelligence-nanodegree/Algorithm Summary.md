## Search

- Local Search
  - Hill-climbing
  - Simulated annealing
  - Local beam
  	- Stochastic beam
  - Genetic algorithm
- Forward Search
  - Uninformed
    - BFS
    - DFS
      - Iterative deepening search
    - Uniform-cost search
    - Bidirectional
  - Informed
    - Generating heuristics
      - From the relaxed problem
      	The heuristic function may still have high cost, since the state space haven’t been diminished
      	- Ignore preconditions on actions
      	- Ignore negative effects on actions
      - From subproblems
      	- Group states to form an abstract state
      	- Pattern database
      - From experience
    - Best-first search 
      - Greedy best-first search
      - A* search
      - Memory-bounded search
      	- Recursive best-first search
      	- Simplified memory-bounded A*
    - Minimax
      - Alpha-beta pruning
      - Forward pruning
      	- Beam search
      	- Probabilistic cut
      - Min/max approximation
    - Beam search
      - Beam-stack search (anytime algorithm)
      	- Divide-and-conquer beam-stack search (anytime algorithm)
- And-or
- Incremental belief-state
- Backtracking
- Online
  - Online DFS
  - Learning real-time A*


- CSP
	- AC-3
	- Backtracking
	- Local
		- Min-conflicts algorithm
		- Constraint weighting
	- Tree-structured CSP solver
- Logic
	- Satisfiability problem
		- WalkSAT (Prop)
	- Entailment problem
		- DPLL (Prop)
		- Backward chaining (definite)
		- Forward chaining (definite)
		- Resolution
## Planning

- Search
  - Progression search
  - Regression search
- Classic plan
  - SAT plan
  - Partial-order plan