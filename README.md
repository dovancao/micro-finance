# micro-finance
Establish peer-to-peer transactions in micro finance

![microfinace](https://user-images.githubusercontent.com/36324165/41702103-10984a0e-7559-11e8-9b3f-42878786f116.png)

# Installation
This project is required NodeJS 8.x.x LTS.

# Dependencies Packages
Microsoft build tools:
```
$ npm i -g -p windows-build-tools
```

Ganache
```
$ npm i -g ganache-cli truffle mkinterface
```

#Testing
Open terminal at the root directory of project:
```
ganache cli
```

then in another terminal:
```
$ truffle migrate --reset && truffle test
```
