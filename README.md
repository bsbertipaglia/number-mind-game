# Solve the game Number Mind using SAT solvers

The game Number Mind is a variant of the well known game Master Mind. Instead of colored pegs, you have to guess a secret sequence of digits. After each guess you’re only told in how many places you’ve guessed the correct digit. So, if the sequence was 1234 and you guessed 2036, you’d be told that you have one correct digit; however, you would NOT be told that you also have another digit in the wrong place.

Solving this game can be done using a combination of PySAT, a Python library for solving Boolean satisfiability problems, and first-order logic, a fundamental approach in mathematical logic.
