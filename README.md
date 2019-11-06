# carrom-react
Carrom-React 
# Install Yarn
npm install -g yarn

# To run the app locally install live-server
yarn global add live-server

# if the above command does not work
npm install -g live-server
# run the project locally
live-server public

# Install Babel
npm install -g babel-cli@6.24.1

# Yarn Lock Initiate
yarn init

# Store the node module dependency
yarn add babel-preset-react@6.24.1 babel-preset-env@1.5.2

#converting jsx to readable js

babel src/app.js --out-file=public/scripts/app.js --prests=env,react
# Live changes
babel src/app.js --out-file=public/scripts/app.js --prests=env,react --watch

# if node modules missing
yarn install
