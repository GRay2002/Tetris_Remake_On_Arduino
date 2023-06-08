# Motion-Controlled Tetris Game with Arduino

This project is a motion-controlled Tetris game implemented using an Arduino UNO R3 and other electronic components. It offers an enhanced and interactive gaming experience by incorporating motion controls through a Rotary Encoder and an MPU6050 3-Axis Accelerometer and Gyroscope Module.

## Features

- Motion controls: Use the Rotary Encoder to rotate and speed up the falling Tetris pieces, and the MPU6050 module to handle left and right movement.
- Classic button controls: For players who prefer a nostalgic experience, the game also supports the traditional two-button combo for playing Tetris.
- Visual display: The game utilizes two MAX7219 LED matrix modules to provide a clear and visible display of the Tetris game board.
- Menu system: A menu system allows users to start and reset the game easily.
- Audio feedback: The passive buzzer plays the beloved Tetris theme song, "Korobeiniki," adding to the immersive experience.

## Hardware Requirements

- Arduino UNO R3
- MAX7219 LED Matrix Display Module x2
- MPU6050 3-Axis Accelerometer and Gyroscope Module
- Rotary Encoder Module
- Push Buttons x2
- Passive Buzzer

## Software Requirements

- Arduino IDE

## Installation

1. Clone this repository to your local machine.
2. Open the Arduino IDE.
3. Connect your Arduino UNO R3 to your computer via USB.
4. Open the `Tetris.ino` file from the cloned repository in the Arduino IDE.
5. Click the "Upload" button in the Arduino IDE to upload the code to your Arduino board.
6. Connect the hardware components according to the provided circuit diagram.
7. Power on the Arduino and enjoy playing the motion-controlled Tetris game!

## Usage

1. Connect the Arduino to a power source.
2. Use the Rotary Encoder to rotate and speed up the falling Tetris pieces. Rotate the lever upwards to rotate the piece and downwards to speed it up.
3. Use the MPU6050 module for left and right movement. Tilt the module left or right to move the Tetris piece in the corresponding direction.
4. Optionally, you can use the traditional button controls to play the game.
5. Enjoy playing Tetris with motion controls and immerse yourself in the nostalgic experience!

## Development Journal

For a detailed development journal and progress updates, please refer to the PDF attached to the realease section.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request.

## Acknowledgements

- Thanks to Badrinath Murugesan (Electro Oxe) for the original Tetris game code.
- Thanks to Robson Couto for the Tetris theme song.
- Thanks to Wayoda Eberhard Fahle for the MAX7219 LedControl library.
- Thanks to Paul Stoffregen for the Encoder library.


---

Feel free to modify and customize the template according to your specific project details. Make sure to provide the necessary links to your development journal, license file, and any other relevant files or resources in your GitHub repository.
