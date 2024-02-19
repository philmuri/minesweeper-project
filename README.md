# MINESWEEPER
Credits go primarily to this youtube video: https://www.youtube.com/watch?v=G9JP8uuQqP0. I experimented with some things out of curiosity and added some additional features.

## Other additions to consider
- Custom size of grid
    - Need to scale cells appropriately by changing the css grid in #minesweeper-board
    - Add html input box for this

- Add alert when round is completed succesfully
    - Check state of all cells if isRevealed or isMine is true?

- Replace confirm() for game over and completion messages with a html element and colorized text


## Known bugs
- Game does not terminate upon succesful board completion
    - Fix: Check each cell is revealed (there might be a faster method)
