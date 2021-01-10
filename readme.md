# Pill Demo

This will be the testing ground for the "Pill" to be used as a placeholder in upcoming projects. 

These pills will be using a 32x32 pixel art style.

## Pill:

A rectangular creature with rounded corners, a 'head' that's discoloured from the rest of its body and disembodied hands and feet.

We will be using the "thin" pill (and adjusting elements of the model in game as we go) with disembodied hands and feet. The hands are so that the pill can pick up items and use things with its hands while the feet are to allow boots to not look out of place once we add them.

### Needs:

Animations:

* Idle
* Walking
* Attack
* Damage
* Death

Extras:

* Running(?)

When it comes to animations, we will be using states to trigger animations therefore a "jump" animation will not draw the character higher.

#### Idle

The idle will just have the pill move up and down. The hands move down first, then the body, the body returns and then we loop.

#### Walk

The feet transform into shoes pointed in the desired direction and the feet begin moving in a believable fashion.

#### Attack

The hands will move in an attacking fashion, this animation may be specific to the hand. 

#### Damage

The pill takes damage...