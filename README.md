# RadioButtonDemo

## Overview

`RadioButtonDemo` is a simple Java Swing application that demonstrates the use of radio buttons to select different pets. When a radio button is selected, an image corresponding to the selected pet is displayed, and a message dialog shows the selected pet's name.

## Features

- Radio buttons for selecting different pets: Bird, Cat, Dog, Rabbit, and Pig.
- Displays an image of the selected pet.
- Shows a message dialog with the name of the selected pet.

## Requirements

- Java Development Kit (JDK) 8 or higher
- Swing library (included in JDK)

## Installation

1. Clone the repository or download the source code.
2. Ensure you have the required images (`bird.png`, `cat.png`, `dog.png`, `rabbit.png`, `pig.png`) in the same directory as the `RadioButtonDemo.java` file.

## Usage

1. Compile the `RadioButtonDemo.java` file:
    ```sh
    javac assignment2/RadioButtonDemo.java
    ```

2. Run the compiled class:
    ```sh
    java assignment2.RadioButtonDemo
    ```

## Code Structure

- `RadioButtonDemo.java`: The main class that creates the GUI and handles the radio button actions.

## How It Works

1. The `RadioButtonDemo` class extends `JFrame` to create a window.
2. Radio buttons for different pets are created and added to a `ButtonGroup` to ensure only one can be selected at a time.
3. An `ActionListener` is added to each radio button to handle the selection event.
4. When a radio button is selected, the `updateImage` method is called to update the displayed image based on the selected pet.
5. The `updateImage` method sets the icon of the `imageLabel` to the corresponding image file.

## Example

When you run the application, you will see a window with radio buttons for Bird, Cat, Dog, Rabbit, and Pig. Selecting a radio button will display the corresponding pet's image and show a message dialog with the pet's name.



## Author

-Egan Ombaka
-BSE-01/0076-2024#
