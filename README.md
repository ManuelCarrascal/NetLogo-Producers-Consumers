# Producers and Consumers Model in NetLogo

This project simulates a number of producers and consumers that produce and consume boxes, respectively. The producers and consumers act concurrently and their behavior is controlled by a semaphore.

## Features

- Each producer can produce a box if the semaphore allows it and there are boxes available to produce.
- Each consumer can consume a box if the semaphore allows it and there are boxes in the buffer to consume.
- The color of the producers changes to blue when they are producing a box and returns to gray once they have finished.
- Consumers turn red when they are consuming a box and return to green once they have finished.

## Setup

The initial setup of the model involves the creation of producers, consumers, and boxes. The number of each can be adjusted as per the requirements.

## Running the Simulation

The simulation runs cyclically with the help of the `go` function. If there are no boxes available to produce or consume, the simulation stops.

## Author

Manuel Alejandro Carrascal Arias

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
