### install yarn
npm install --global yarn

### fix/add yarn global PATH
export PATH="$PATH:$(yarn global bin)"

### install typescript
yarn global add tsc typescript ts-node ts-node-dev

### init
npm init --y
tsc --init
yarn add express
yarn add @types/express --dev

### update tsconfig.json (allowJS, rootDir, outDir)
### update package.json (add yarn script - start)

# Start run this project
yarn start
