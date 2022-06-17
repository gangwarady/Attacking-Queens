# Attacking-Queens

So many Queens, how to manage?
During a gladiatorial contests at the roman empire, a fine king invited all his queens to witness the valour of the gladiators. However, the queens were not in likings of one-another and must not see eye-to-eye. Your job as the "Minister of Strategies" in King's office is to create a sitting arrangement for all queens, while keeping in mind that no two queens are in the "LINE OF SIGHT" of one another i.e. the queens must be avoided to be in the same row or column or diagonally.

The "minister of Strategies" had recently enrolled in the Class of Artificial Intellignece CS 512 and decided to use A* algorithm to solve the problem.

Heuristic to be used for this problem is " Number of attacked queens", where if any new queen is placed in "LINE of ATTACK" of other queen, the Heuristic is incremented by 1, else it is unchanged.

Can you propose a better heuristic for this problem? If yes, then compare the performance of A* with your proposed and the given heuristic. [15 marks]

The G(n) function can be defined as the number of queens which are correctly placed at the given time. For eg: if the state is
0 0 1 0

1 0 0 0

1 0 0 0

0 0 0 1

then only one queen is correctly placed while, three queens are in ATTACK mode.

Reference image
8queen.png
