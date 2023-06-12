# anon-aadhaar

## About project

## Requirements 
Install `rust` and `nodejs`.

## Install and test


Install nodejs dependencies. 
```bash
yarn
```

Install `circom` and download powers of tau file. 

```bash 
./script/setup-dev.sh install
```

Generate verification key and proving key.

**NOTE:This action use for development only. Don't use it in product, please!**

```bash
./script/setup-dev.sh setup  
```

Run test 
```bash
yarn test
```