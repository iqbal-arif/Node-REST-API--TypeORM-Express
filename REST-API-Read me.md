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
