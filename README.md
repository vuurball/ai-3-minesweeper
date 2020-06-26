### AI Minesweeper Player 

The goal in this project will be to build an AI that can play Minesweeper. Knowledge-based agents make decisions by considering their knowledge base, and making inferences based on that knowledge.

One way we could represent an AI’s knowledge about a Minesweeper game is by making each cell a propositional variable that is true if the cell contains a mine, and false otherwise.

The information the AI have access to - the AI would know every time a safe cell is clicked on and would get to see the number for that cell. 

we’ll represent each sentence of our AI’s knowledge like the below.

`{A, B, C, D, E, F, G, H} = 1`

Every logical sentence in this representation has two parts: a set of cells on the board that are involved in the sentence, and a number count, representing the count of how many of those cells are mines. The above logical sentence says that out of cells A, B, C, D, E, F, G, and H, exactly 1 of them is a mine.

![](https://github.com/vuurball/ai-3-minesweeper/blob/master/demo.gif)