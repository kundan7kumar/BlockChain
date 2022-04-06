# BlockChain



#### Run the development console. 
truffle develop

##### Compile and migrate the smart contracts. Note inside the development console we don't preface commands with truffle.

compile
migrate

#### In the app directory, we build and run our frontend. Smart contract changes must be manually recompiled and migrated. 
// in another terminal (i.e. not in the truffle develop prompt)
cd app
npm run dev

#### Truffle can run tests written in Solidity or JavaScript against your smart contracts. Note the command varies slightly if you're in or outside of the development console. 

// inside the development console.
test

// outside the development console..
truffle test

### To build the application for production, use the build script in the app folder. A production build will be in the app/dist folder. 
// ensure you are inside the client directory when running this
npm run build


Framework using https://trufflesuite.com/boxes/webpack/
