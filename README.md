# Tic-Tac-Toe-Game using javascript

A TicTacToe game with minimax algorithm

## Use

Start the game with "game.html"

## Minimax algorithm

A description for the algorithm, assuming X is the "turn taking player," would look something like:

- If the game is over, return the score from X's perspective.
- Otherwise get a list of new game states for every possible move
- Create a scores list
- For each of these states add the minimax result of that state to the scores list
- If it's X's turn, return the maximum score from the scores list
- If it's O's turn, return the minimum score from the scores list

You'll notice that this algorithm is recursive, it flips back and forth between the players until a final score is found.

## Illustration

![Image of the first tree]( https://images.squarespace-cdn.com/content/v1/5a0c6978bff2001ef7581170/1513544600041-LK94ONS0M8TSFUFCPPNB/ke17ZwdGBToddI8pDm48kM0UFzSX-GmXGE6uzfQKFGcUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKcNGYpWN1nf4nUUVDcP3FLfN51GxsaWT80qRWhr6f2ozjeHnMLFnDWbx-N21Y6qvac/full-minimax-move-tree.png?format=1500w)
