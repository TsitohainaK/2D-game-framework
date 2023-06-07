# 2D Game Framework written in TypeScript

This is a 2D game framework built with TypeScript, following the Entity-Component-System (ECS) architecture and utilizing the Matter.js physics engine. The framework enables the development of 2D games with realistic physics interactions.

> ps: I'm just begining in designing this such of thing, so feel free to tell me what i can improuve. Also I do it just for fun.

## Features

- **ECS Architecture**: The framework is designed using the Entity-Component-System architecture, which provides a flexible and scalable approach to building game entities and systems. It allows for easy composition of game objects and separation of concerns.

- **TypeScript**: The framework is written in TypeScript, bringing the benefits of static typing and enhanced tooling support. TypeScript helps catch errors during development and provides better code maintainability.

- **Vite as Bundler**: The framework utilizes Vite as the bundler, offering fast development server with hot module replacement and efficient production builds.

- **Matter.js Physics Engine**: The framework integrates the Matter.js physics engine to handle realistic physics simulations in the game. Matter.js provides an efficient and robust physics engine for 2D games, including collision detection and response.

- **Game Loop**: The framework includes a game loop implementation that handles rendering, input handling, physics calculations, and updating game entities. It ensures smooth and consistent gameplay experience.

- **Sprite Rendering**: The framework supports sprite rendering, allowing for the display of 2D graphics and animations in the game. It provides mechanisms for loading and rendering sprites, as well as managing sprite animations.

- **Input Handling**: The framework includes input handling capabilities, allowing for user interaction with the game through keyboard or mouse events. It provides an abstraction layer for easy access to input states and actions.

## Installation

1. Clone the repository: `git clone https://github.com/TsitoUw/2D-game-framework.git`
2. Navigate to the project directory: `cd game-framework`
3. Install the dependencies: `npm install`

## Usage

1. Start the development server: `npm run dev`
2. Open your browser and visit: `http://localhost:1080`

## Deployment

To deploy your game to a production environment, follow these steps:

1. Build the optimized version of the project: `npm run build`
2. The build output will be located in the `dist` directory.
3. Deploy the contents of the `dist` directory to your desired hosting platform.

## Credits

- This project utilizes the following libraries and frameworks:
  - [TypeScript](https://www.typescriptlang.org)
  - [Vite](https://vitejs.dev)
  - [ECS](https://en.wikipedia.org/wiki/Entity%E2%80%93component%E2%80%93system)
  - [Matter.js](https://brm.io/matter-js/)
  
## License

The game framework is open-source and available under the [MIT License](LICENSE). Feel free to modify and use it to develop your own 2D games.

## Contact

If you have any questions or feedback, please feel free to reach out to me at [tsitohaina.pro@gmail.com](mailto:tsitohaina.pro@gmail.com).
