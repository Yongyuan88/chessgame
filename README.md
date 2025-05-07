# chessgame
```python
class ChessGame:
    def __init__(self):
        self.board = self.create_board()
        self.current_player = 'White'

    def create_board(self):
        board = [
            ['r', 'n', 'b', 'q', 'k', 'b', 'n', 'r'],
            ['p'] * 8,
            [' '] * 8,
            [' '] * 8,
            [' '] * 8,
            [' '] * 8,
            ['P'] * 8,
            ['R', 'N', 'B', 'Q', 'K', 'B', 'N', 'R']
        ]
        return board

    def print_board(self):
        for row in self.board:
            print(' '.join(row))

    def switch_player(self):
        self.current_player = 'Black' if self.current_player == 'White' else 'White'

    def play_game(self):
        while True:
            self.print_board()
            print(f"{self.current_player}'s turn.")
            move = input("Enter your move (e.g. a2a4): ")
            # Implement move logic here
            self.switch_player()

if __name__ == "__main__":
    game = ChessGame()
    game.play_game()
```
