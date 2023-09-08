# Battleship

This is Battleship game implemented using C++.
The game can be played by 2 people against each other, or by one person against a
robot of easy, medium, or hard difficulty. I implemented the ship placement and
attack method for all three difficulties. The player is able to choose what size board
they want to play on and what kind of opponent they would like to play.

What the implementation does:
My implementation is able to restrict the player from placing ships that overlap other
ships that have been placed or that have sections of the ship hanging off the edge of
the board. The implementaion also restricts the player from attacking a position that is
not on the board or that they have already attacked. The ships can be placed horizontally
or vertically at any point on the board, as long as the full ship is on the board. The
implementation also keeps track of the game for the player with two different boards. This
allows the player to see where they have attacked/hit the opponent on one board and where
their ships are along with where the opponent has attacked/hit on another board.
The game will also detect when the game is over.
