# User Profile Information

This is a react project that display the users information.

# How to run the project

## In one terminal start the server by executing

```bash
npm start
```

## In another terminal run below command to automatically build any changes in public folder

```bash
npm run watch
```

### Additonal details for reference

- npm init
- npm install express@4
- node server.js - To start the server
- npm start - Alternative way to start the server
- npm install --save-dev @babel/core@7 @babel/cli@7 - Babel compiler and cli to do transform
- npm install --save-dev @babel/preset-react@7 - To converst JSX syntax to JavaScript
- npx babel src --presets @babel/react --out-dir public - Command to read from src folder and output \* javascript to public folder
- npm install --no-save @babel/plugin-transform-arrow-functions@7 - To tranform arrow functions and support older browsers
- Configuration file .babelrc - Configuration file
- npx babel src --out-dir public - To trasform jsx to public dir
- npm run compile - Can use this command after adding in compile in package.json
- npm install nodemon@1 - On updates on server side, it restart node.js with latest changes
- npm run watch - Looking for recent changes
- npm start - To start the server
