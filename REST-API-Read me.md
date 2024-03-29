**\*** Project Setup **\***

1. Initialize Project: npm init
2. Script in JSON: Delete script in package.json
3. Install Typescript: npm install --save-dev typescript
4. File Exclusion: .gitignore => enter the list
   .idea
   \*.js
   node_modules
   dist
   .env
   rest-api/logs
5. Git Setup
   1. Initialize Git: git init
   2. Remote Access to git Repository: git remote add origin https://github.com/iqbal-arif/Node-REST-API--TypeORM-Express.git
   3. Commit changes.
6. Typescript Configuration:
   {
   "compilerOptions": {
   "target": "ES5",
   "outDir": "dist"
   }
   }
7. Package JSON configuration:
   "scripts": {
   "build": "tsc",
   "start-server": "node dist/server.js"
   },
8. File compilation: tsc
9. App Launch: npm run build
10. To run the .ts file and get result: npm run start-server
11. Typescript Continuous UPdate: tsc -w
12. Install Express normal dependency: npm install --save express
13. Install Express for Typescript dependency: npm install --save-dev @types/express
14. Install rimraf to clean /dist folder at the beginning of build process: npm install --save-def rimraf
15. Install cross-platform module: npm install --save-dev npm-run-all

**\*** SERVER Setup **\***

1. Server Logic: server.js
2. Routes HTTP Logic: route.ts
3. Compile: npm run build if this does not work then try tsc or tsc -w
4. Start Server: node dist/server.js

/****\*\***** npm notes ******\*******

    delete the node modules folder by running rm -rf node_modules
    delete package.lock.json file by running rm -f package-lock.json
    clean up the NPM cache by running npm cache clean --force
    install all packages again by running npm install
