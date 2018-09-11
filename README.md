# Hex Board

This is a ruby erb template to generate an SVG image of a [Hex](https://en.wikipedia.org/wiki/Hex_(board_game)) board.  The original intent is for laser cutting and laser etching a board to play.

To generate an svg from the file, you need the ruby `erb` command:

```
erb hexboard.svg.erb > hexboard.svg
```

You can modify some of the constants at the top of `hexboard.svg.erb` to change things like the line colors or the size of the board.
