# PROTO-AI-ML-STM32F446

An experimental project to run a simple neural network on a STM32F446RE Nucleo board.
Branches of this project are used to test different project configurations/runtimes/etc.

## Conversion to CPP

Using the TensorFlow runtime requires converting the project to CPP. This is done by right clicking on the project and selecting "Convert to C++".

## Building the template

Using the application template builds absolutely everything from the TensorFlow library which is not necessary, and takes a long time.

Where can we set only the necessary libraries to build from the IDE?
