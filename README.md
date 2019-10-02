

LATEST BUILD: Version 0.4 RELEASE DATE: 10/01/19 /////////////////////////////////////////////////////////////////////////////////////////////

Welcome! This is a webgl build of a character action controller I'm developing in Unity.
With this project I hope to create a basic general character action controller template for use in future Unity projects.\

Demo Link: https://spicygarlicalbacoreroll.github.io/characterActionControllerDemo/index.html

/////////////////////////////////////////////////////////////////////////////////////////////

CHANGELOG:\

VERSION 0.4\

Added coyote jump when jumping immediately within 3 seconds after walking off ledge. Have giant untouchable block for state machine testing purposes \

VERSION 0.3\

Implemented a simple Finite State Machine, which will be used for the combo system. Currently only has player freeze their position for 0.3 seconds with each attack state. Will add hitbox/hurtbox for visual debugging attacks (whenever I get around to implementing actual assets)\

/////////////////////////////////////////////////////////////////////////////////////////////

CONTROLS: (XBOX ONE controllers should be supported in browser, at least on Linux in Firefox)
MOVEMENT: WASD Controls / Left Joystick
JUMP/DOUBLEJUMP: Spacebar/A
DASH: Hold LEFT SHIFT while moving in direction (has couple second cooldown)
CAMERA: Mouse / Right Joystick (press M to toggle between them)
RESET POSITION: R

MELEE: (Only freezes player,no animations or hit/hurt boxes)
    HEAVY ATTACK: G / Y
    LIGHT ATTACK: F / X

/////////////////////////////////////////////////////////////////////////////////////////////

PROJECT GOALS . . .

    Fast and snappy movement [WORKING, IN PROGRESS]

    Double Jumps [DONE]

    Wall Jumps

    Dashes [WORKING, IN PROGRESS]

    Hit and Hurt boxes

    Streamlined method of creating combos
    -Implement via Finite State Machine [WORKING, IN PROGRESS]

    Add enemies to showcase features and playtest

/////////////////////////////////////////////////////////////////////////////////////////////
