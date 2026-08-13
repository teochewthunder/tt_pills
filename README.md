# Pill Puzzle
You are slowly dying. There are 8 pills. 7 of them are lethal poison, and 1 of them is the cure. That pill is lighter than the rest of them, but in any other discernable way, it is identical. There is a scale which may be used two times.

## HTML/CSS
The HTML uses a grid-Flexbox combination. This is especially pertinent during the weighting operation. The "heavier" side "sinks" while the "lighter" side "rises". This is accomplished by use of
- `display`: `flex`
- `flex-direction`: `column`
- `justify-content`: `flex-start` | `flex-end` | `center`

## JavaScript
- uses jQuery to simplify DOM manipulation
- use `reduce()` to sum up weights.
- use `splice()`, `unshift()` and `push()` to manipulate arrays.
