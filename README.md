# Number-Maze-Game
Fork of @technoblogy [https://github.com/technoblogy/number-maze-game] handheld game that displays logic mazes you have to solve by pressing the buttons.

For the original version see: http://www.technoblogy.com/show?45JT.

For the updated version, with additional harder mazes, see: http://www.technoblogy.com/show?48BN.

## Changes
 * Translate intro & game No. to CZECH
 * modify sleep routine

## Adrino IDE settings:    
 * DxCore 1.5.11
 * AVR DA Series (no bootloader)
 * AVR128DA32
 * millis() TCB2
 * Clock 4MHz
 * printf() minimal

# ⚠️ AVR32DA32 WARNING
## There is an issue in TCB0_INT_vect (DxCore)[https://github.com/SpenceKonde/DxCore]
## Use AVR32_NumberMageGame sketch
 * Port David's sketch to AVR32DA32 with DxCore 1.5.3
 * Translate intro & game No. to CZECH
 * no millis, no TCB used = Its some issue w/ iterrupts or something around TCB, I thing
 * modify sleep routine
 *      
 * Adrino IDE settings:    
 * DxCore 1.5.3
 * AVR DA Series (no bootloader)
 * AVR32DA32
 * millis() disabled
 * Clock 4MHz
 * printf() minimal
