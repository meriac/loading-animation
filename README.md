![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg)

# Rotating Dash by Andre & Milosch Meriac #

## Notes on submission for Chip Tape-Out (tt02) ##
This is the submission repository for taping out [our custom chip-design](https://meriac.github.io/loading-animation)
as part of the [TinyTapeout](https://tinytapeout.com/) (tt02) project.

Our project shows an automated rotating dash - or can be switched to a
step-by-step mode using the built-in button. You can find the "code" of
our chip design project [here at WokWi](https://wokwi.com/projects/348121131386929746).

![Rotating Dash on 7-Segment display](https://raw.githubusercontent.com/meriac/loading-animation/main/img/loading-animation.png)

## How It Works ##
Slide switch to external clock. All DIP switches to off. DIP2 (Reset) on to run (Reset is low). By switching DIP3 (Mode) on and setting the sliding switch to Step-Button, the Step-Button can be now used to animate step by step.

## How To Test ##
Slide switch to external clock. All DIP switches to off. DIP2 (Reset) on
to run (Reset is low-active).
