conduct leaf wall visit acid ask trumpet win country vault pig security





commands
- ganache-cli
- truffle migrate --reset
- npm run start


Order of operations
1. truffle unbox react
2. change truffle.js and getWeb3.js (line 24) files as indicated
3. run > ganache-cli and copy mneumoic
4. paste the mneumonic to metamask and go to localhost:8545
5. run > truffle migrate --reset
6. npm run start


-------- Steps I took
1. truffle unbox react-uport
2. go to appmanger.uport.me
3. create uport account. Instead of signing in you, use your phone to authenticate requests


Need to Figure out how to:
- https://ethereum.stackexchange.com/questions/38865/how-to-deploy-a-truffle-app-in-heroku
- For the connect uport, make sure to put in on the server somewhere in a lambda function
- Persist uPort Login in local storage