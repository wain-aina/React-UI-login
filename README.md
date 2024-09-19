Open two tabs, each in the project directory.

In one tab, cd into the public folder, run:

### `npm install`

This will install all node modules in the package.json file for the React frontend

In the second tab, cd into the server folder, run:

### `npm install`

This will install all node modules in the package.json file for the NodeJS backend


Once all the modules are installed, while in the public folder, run:

### `npm start`

This will start the React server in dev mode.

Open [http://localhost:3000] to view it in your browser.

At the same time, in a separate tab, while in the server folder, run:

### `npx nodemon index` 

This will start the Express/NodeJS backend server on port 4000.
