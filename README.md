# front-end-challenge-transactions-list

Code challenge for an investment brokerage and management company.

> [!NOTE]  
> This repository was originally created in 2022, but was modified in 2024 to hide the company name for security reasons and also translated to English.

Demo link: <https://front-end-challenge-transactions-list.netlify.app/>

## About the challenge

This challenge involved implementing a transaction list page, displaying key data for each transaction. When a transaction is clicked, a modal with the transaction details is shown. The challenge required the following features:

- [x] Transaction list grouped by date
- [x] Filter by title
- [x] Filter by status
- [x] Modal with transaction details

### Technologies

- Vue2 with CLI
- TypeScript
- Less
- Axios
- Jest

The choice of technology was based on the requirements of XXX Company, so I used the closest tools to what was requested.

## Installation of dependencies

### Prerequisites

The following software is required to use the application:

- [git](https://git-scm.com/): Used to clone the project repository.
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/): Package manager for automatically installing project dependencies.
- [Node.js](https://nodejs.org/en/): Runtime required for using the package manager and running the application.
- [Vue CLI](https://cli.vuejs.org/guide/installation.html): Vue CLI serves as the standard toolset for the Vue ecosystem.

### Installation

Steps to install the project:

1. Clone the repository:

   Using HTTPS:

   ```sh
   git clone https://github.com/johanguse/front-end-challenge-transactions-list.git
   ```

2. Navigate to the project folder:

   ```sh
   cd front-end-challenge-transactions-list
   ```

3. Install the necessary packages:
   
   Using yarn (inside the project folder):

   ```sh
   yarn
   ```

   Using npm (inside the project folder):

   ```sh
   npm install
   ```

## Usage

> Note: Change the command from **yarn** to **npm run** if you're using _npm_ instead of _yarn_ as your package manager.

The project includes 3 script commands to run the application:

To start the project in development mode:

```sh
yarn serve
```

To build the project for production with optimized files:

```sh
yarn build
```

To run the project's unit tests:

```sh
yarn test:unit
```

## To-Do

Some things that still need to be implemented or changed in the project:

- [ ] Create more unit tests (Jest)
- [ ] Create E2E tests (Cypress)