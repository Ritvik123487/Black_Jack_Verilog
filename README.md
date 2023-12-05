# Black_Jack_Verilog

Project created in verilog to mimic a casiino blacjack game - player vs CPU.

VGA device and FPGA required for user interface and graphics

Notes:
- All Verilog modules are contained in fill.v
- MIF files are required to display the cards to VGA
- Will need to use quartus prime to run the code (MacOS currently does not support this)

About:
- Utilized a Field Programmable Gate Array (FPGA) as the hardware platform to run the Black Jack game, with game logic and control mechanisms meticulously designed using Verilog HDL. This includes the implementation of a finite state machine (FSM) for game state transitions, a linear feedback shift register (LFSR) for random number generation to simulate card shuffling, and data paths that facilitate the movement and processing of game information.
- Engineered a VGA interface within the FPGA to display the game's graphical output, allowing players and the CPU to interact visually with the game. This interface presents the drawn cards and game status on a monitor, offering an immersive gaming experience through hardware-level rendering.
- Developed a comprehensive system that includes onboard memory for storing the state of the game, such as the deck of cards and the hands of players. Implemented rate dividers to control the pace of the game, ensuring that it runs at a user-friendly speed and that the VGA display refreshes at the correct rate for a stable visual output.

