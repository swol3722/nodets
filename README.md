# Sample NodeJS Project with TypeScript

This repository contains a NodeJS project setup with TypeScript for development purpose.

## Prerequisite

Please ensure that you have installed NodeJS v18.16.0 or above with Yarn v1.22.19.

## How to Setup?

1. Clone the project into a desired location.
2. Inside the project root directory, execute the command `yarn run setup` or `yarn run setup:pwsh` if you are using Windows platform with PowerShell terminal.
   * The `setup` script installs all required dependencies and setup the project for module aliases.
   * Please fill in the varibale values of the newly created `.env` file as appropriate.

## Project Execution

1. Execute the command `yarn run start:dev` inside the project root directory for development mode.
   * This command spins up a Nodemon server with hot reloading capability.
   * Please make sure that all your project source code is available within the `src` directory and treat `src/index.js` file as the entry point of the program.
2. Execute the command `yarn run start` inside the project root directory for production mode.
   * All the TypeScript source code will be compiled to JavaScript in the `build` directory.
   * The entry file `build/index.js` will be executed by Node.

## Utility Scripts

1. All the testing scripts can be executed with `yarn run test` command.
2. The source code can be checked for linting issues with `yarn run lint` command.
3. Execute `yarn run lint-and-fix` command to check and auto fix the fixable linting issues.
4. Source code formatting can be done with `yarn run format`.
