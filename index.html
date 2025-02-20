<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic Tac Toe - Dark Blue Theme</title>
    <style>
        body {
            font-family: sans-serif;
            background-color: #1a237e; /* Dark Blue Background */
            color: #fff; /* White Text */
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }

        .container {
            text-align: center;
        }

        h1 {
            margin-bottom: 20px;
            color: #bbdefb; /* Lighter Blue for Heading */
        }

        .board {
            display: grid;
            grid-template-columns: repeat(3, 100px);
            grid-gap: 5px;
            margin-bottom: 20px;
        }

        .cell {
            width: 100px;
            height: 100px;
            background-color: #303f9f; /* Darker Blue for Cells */
            color: #fff;
            font-size: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            border: 1px solid #283593; /* Even Darker Blue for Border */
        }

        .cell:hover {
            background-color: #3949ab; /* Slightly Lighter Hover */
        }

        .status {
            font-size: 20px;
            margin-bottom: 10px;
            color: #bbdefb;
        }

        button {
            background-color: #5c6bc0; /* Button Background */
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
        }

        button:hover {
            background-color: #6a1b9a; /* Button Hover */
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Tic Tac Toe</h1>
        <div class="status">Player X's turn</div>
        <div class="board">
            <div class="cell" data-index="0"></div>
            <div class="cell" data-index="1"></div>
            <div class="cell" data-index="2"></div>
            <div class="cell" data-index="3"></div>
            <div class="cell" data-index="4"></div>
            <div class="cell" data-index="5"></div>
            <div class="cell" data-index="6"></div>
            <div class="cell" data-index="7"></div>
            <div class="cell" data-index="8"></div>
        </div>
        <button id="restartBtn">Restart Game</button>
    </div>

    <script>
        const cells = document.querySelectorAll('.cell');
        const status = document.querySelector('.status');
        const restartBtn = document.getElementById('restartBtn');
        let currentPlayer = 'X';
        let gameActive = true;
        let gameState = ["", "", "", "", "", "", "", "", ""];

        const winningConditions = [
            [0, 1, 2],
            [3, 4, 5],
            [6, 7, 8],
            [0, 3, 6],
            [1, 4, 7],
            [2, 5, 8],
            [0, 4, 8],
            [2, 4, 6]
        ];

        function handleCellClick(clickedCellEvent) {
            const clickedCell = clickedCellEvent.target;
            const clickedCellIndex = parseInt(clickedCell.getAttribute('data-index'));

            if (gameState[clickedCellIndex] !== "" || !gameActive) {
                return;
            }

            handleCellPlayed(clickedCell, clickedCellIndex);
            handleResultValidation();
        }

        function handleCellPlayed(clickedCell, clickedCellIndex) {
            gameState[clickedCellIndex] = currentPlayer;
            clickedCell.textContent = currentPlayer;
        }

        function handlePlayerChange() {
            currentPlayer = currentPlayer === "X" ? "O" : "X";
            status.textContent = `Player ${currentPlayer}'s turn`;
        }

        function handleResultValidation() {
            let roundWon = false;
            for (let i = 0; i <= 7; i++) {
                const winCondition = winningConditions[i];
                let a = gameState[winCondition[0]];
                let b = gameState[winCondition[1]];
                let c = gameState[winCondition[2]];
                if (a === '' || b === '' || c === '') {
                    continue;
                }
                if (a === b && b === c) {
                    roundWon = true;
                    break;
                }
            }

            if (roundWon) {
                status.textContent = `Player ${currentPlayer} wins!`;
                gameActive = false;
                return;
            }

            let roundDraw = !gameState.includes("");
            if (roundDraw) {
                status.textContent = `Draw!`;
                gameActive = false;
                return;
            }

            handlePlayerChange();
        }

        function handleRestartGame() {
            gameActive = true;
            currentPlayer = "X";
            gameState = ["", "", "", "", "", "", "", "", ""];
            status.textContent = `Player X's turn`;
            cells.forEach(cell => cell.textContent = "");
        }


        cells.forEach(cell => cell.addEventListener('click', handleCellClick));
        restartBtn.addEventListener('click', handleRestartGame);
    </script>

</body>
</html>
