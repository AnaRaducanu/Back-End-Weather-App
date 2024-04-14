# Back-End-Weather-App

1. npm init -y
2. npm i express
3. npm i --save-dev typescript @types/express @types/node
4. npx tsc --init
5. change commonjs to es6
6. npm run build >>> dist folder is created with server.js inside
7. npm start to start the server

The dist folder is the directory where TypeScript transpiles the .ts files into .js files. The dist folder and server.js are generated after running the npm run build command, which compiles the TypeScript code to JavaScript as per the configuration in tsconfig.json. This folder is not directly created or modified by the developer; it's managed through the build process controlled by the TypeScript compiler.
