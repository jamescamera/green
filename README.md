# Walking Men Worldwide

An animated wall of 42 pedestrian "green man" signals from cities around the world, drawn after the *Walking Men Worldwide* poster.

Open `index.html` in a browser. It is a single file with no build step and no dependencies.

- Each signal runs its own cycle: walk, a flashing countdown, then a red "don't walk" figure drawn in the same style.
- Five lens styles are rendered in code from one skeleton model: solid (with prismatic texture), LED matrix, LED outline, LED line, plus segmented and block lenses.
- Controller: cycle, all walk, all stop, a green wave sweep, a solid/LED filter, and a toggle for the walking animation.
- Tap a signal to open its crossing: a two-lamp signal head, a push button with a WAIT lamp, and an optional audible crossing tick.
