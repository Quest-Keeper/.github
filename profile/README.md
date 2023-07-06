# Quest Keeper

Welcome to Quest Keeper, an application for Dungeons and Dragons enthusiasts, particularly Dungeon Masters, to help in managing and enhancing gameplay.

## Overview

Quest Keeper consists of two main components:

1. **Frontend:** Built using React.js, it provides a dynamic and user-friendly interface.
2. **Backend:** Developed using Ruby on Rails, it acts as an API server to manage the data.

## Frontend

The frontend of Quest Keeper is built with React.js. The project is set up with the create-react-app boilerplate. It utilizes the React Router for navigation and Axios for making HTTP requests to the backend server.

Notable components include:

- **Campaign Manager:** An intuitive interface for managing and organizing your campaigns.
- **Character Generator:** A tool for generating random characters with various traits and attributes.
- **Encounter Builder:** Easily build encounters with a dynamic interface.
- **Initiative Tracker:** A helpful tool for keeping track of turn order in encounters.
- **Item Search:** A robust search feature that allows you to find specific items or loot.
- **Loot Generator:** A feature that generates random loot based on certain parameters such as type, rarity, and amount. The generated items are displayed on the webpage dynamically.

## Backend

The backend of Quest Keeper is a Ruby on Rails server. It's been designed as a RESTful API that serves data to the frontend and also handles various computations required for the application's features.

Notable endpoints include:

- **/api/v1/loot:** The loot endpoint is used by the LootGenerator component. It provides random loot items based on parameters such as type, rarity, and amount.
- **/api/v1/characters:** This endpoint is responsible for the creation of random characters.
- **/api/v1/monsters:** This endpoint serves the monster data based on certain criteria like Challenge Rating (CR).

## Getting Started

To get started with the Quest Keeper project, you'll need to clone both the frontend and backend repositories and follow the setup instructions in each of their READMEs.


Thank you for checking out Quest Keeper! Enjoy your adventure!
