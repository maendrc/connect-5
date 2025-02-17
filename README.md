# connect-5

This is a classic two-player arcade game with a hybrid between
Tic-Tac-Toe and Connect-5. Black piece starts first, and white piece is played
second.

To simulate the hardware level performence, one can use the CPUlater (For Nios II system) web page (https://cpulator.01xz.net/?sys=nios-de1soc&d_audio=48000)

Press [Space] to start the game, and black piece is ready to start. Pieces
are placed randomly on the screen with each [space]; this was implemented
to make the game interactive so the players are encouraged to make a move,
instead of always placing the pieces at one spot on the screen.
Press [H] at any time during the game to display the Help Screen, and
press [enter] to resume the game.
If a piece tries to move past the screen/bounds, an error message shows
up with audio, and the player can try again. If a piece tries to place on an
already-occupied spot, an error message shows up and the player can try
again.
When a Connect-5 is detected, the screen shows who won the round,
and a new round is issued, with the Scoreboard displayed on the LEDs.
(LEDS [0-4] displays Player 1’s score, and LEDS [5-9] displays Player 2’s.)
Best 2 rounds out of 3 wins the game, with a visual and text included at
the end, and the game restarts automatically.
Voice-overs and added sound-effects are included to make the game
more interactive.
Note: When running on CPUlator, make sure to turn off : Memory: Suspicious use of
cache bypass under Debugging Checks.
