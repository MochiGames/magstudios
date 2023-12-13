<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Silkscreen&display=swap">
  <style>
    body {
      background-color: transparent;
      display: flex;
      flex-direction: column;
      align-items: center;
      height: 100vh;
      margin: 0;
      font-family: 'Silkscreen', monospace;
    }

    h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .ferrari-red {
      color: #dc0000; /* Ferrari Red */
    }

    .ferrari-yellow {
      color: #f1c40f; /* Ferrari Yellow */
    }

    #board {
      display: grid;
      grid-template-columns: repeat(3, 100px);
      grid-gap: 5px;
    }

    .cell {
      width: 100px;
      height: 100px;
      background-color: #dc0000; /* Ferrari Red */
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 32px;
      color: #f1c40f; /* Ferrari Yellow */
      cursor: pointer;
    }

    #message {
      margin-top: 20px;
      font-size: 24px;
      color: #fff;
    }

    #play-again {
      margin-top: 10px;
      background-color: #dc0000; /* Ferrari Red */
      color: #f1c40f; /* Ferrari Yellow */
      padding: 10px;
      cursor: pointer;
      border: none;
      font-size: 18px;
    }
  </style>
  <title>Tic Tac Toe</title>
</head>
<body>

<h1><span class="ferrari-red">Ferrari</span> <span class="ferrari-yellow">Games</span></h1>
<div id="board"></div>
<div id="message"></div>
<button id="play-again" class="ferrari-red">Play Again</button>

<script>
  const board = document.getElementById('board');
  const message = document.getElementById('message');
  const playAgainBtn = document.getElementById('play-again');
  const cells = Array.from({ length: 9 }, (_, index) => createCell(index));

  let gameActive = true;

  function createCell(index) {
    const cell = document.createElement('div');
    cell.classList.add('cell');
    cell.dataset.index = index;
    cell.addEventListener('click', () => handleCellClick(index));
    board.appendChild(cell);
    return cell;
  }

  function handleCellClick(index) {
    if (!gameActive) return;

    const currentPlayer = board.dataset.currentPlayer || 'X';
    if (!cells[index].innerText) {
      cells[index].innerText = currentPlayer;
      board.dataset.currentPlayer = currentPlayer === 'X' ? 'O' : 'X';

      if (checkWin()) {
        displayMessage(`${currentPlayer} has won the game!`);
        gameActive = false;
      } else if (checkDraw()) {
        displayMessage("It's a draw!");
        gameActive = false;
      }
    }
  }

  function checkWin() {
    const winPatterns = [
      [0, 1, 2], [3, 4, 5], [6, 7, 8],
      [0, 3, 6], [1, 4, 7], [2, 5, 8],
      [0, 4, 8], [2, 4, 6]
    ];

    for (const pattern of winPatterns) {
      const [a, b, c] = pattern;
      if (cells[a].innerText && cells[a].innerText === cells[b].innerText && cells[a].innerText === cells[c].innerText) {
        highlightWinningCells(pattern);
        return true;
      }
    }

    return false;
  }

  function checkDraw() {
    return cells.every(cell => cell.innerText !== '');
  }

  function highlightWinningCells(pattern) {
    pattern.forEach(index => cells[index].classList.add('win-cell'));
  }

  function displayMessage(msg) {
    message.innerText = msg;
  }

  function resetBoard() {
    cells.forEach(cell => {
      cell.innerText = '';
      cell.classList.remove('win-cell');
    });

    board.dataset.currentPlayer = 'X';
    message.innerText = '';
    gameActive = true;
  }

  playAgainBtn.addEventListener('click', resetBoard);
</script>

</body>
</html>

