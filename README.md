# Simon-Says-Piano-Game-using-8051-Micro-Controller

In this project, an 8051 microcontroller was used to create an 8-button piano with 2 modes: Piano and Simon Says game. The user can select the piano mode to play the miniature piano to their own will. 

If they wish to challenge themselves, they can select the Simon Says mode which will play a series of notes the user must repeat. This mode has a total of 7 levels which increases the difficulty of the game as the level’s increases. 

A binary display using 3 LEDs has been used to keep track of the score. If the user fails to complete a level, the device will signal the user of the error and clear the LED display of the score and reset the game from level 1.

## Hardware Components & Design

The AT89S51 low-power, high-performance CMOS 8-bit microcontroller using 8051 MCU with 4K
bytes of In-System Programmable Flash memory was used for this project. To create the notes, a 12MHz crystal oscillator was used with the frequency of the notes ranging from 1046Hz to 2094Hz.  This circuit works on a 9V power source. The 9V power given in the VCC is stepdown to 5V by the transistor (voltage regulator). The type of voltage regulator used in this device is 7805 series integrated circuit.

The circuit and PCB was designed using PSpice and Eagle Lite respectively. A detailed list of components along with flow charts and block diagram of the system is available in the report. 

## Usage

After connecting the components, the code needs to be adjusted following the connections with the buttons. Keil Uvison was used to edit and burn the code into the MCU. You can find a demo video of the working model to see its performance. 

[Demo Video](https://drive.google.com/file/d/0B1qf2kTwHhuGZ295MFpzRGlWT1E/view?usp=sharing&resourcekey=0-GH83B0h5Bq0WCHwcQOHLnQ)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)