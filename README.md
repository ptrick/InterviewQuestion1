# Trans Lifeline Interview question

[![Build Status](https://dev.azure.com/pworthey007/Interview%20Question%201/_apis/build/status/ptrick.InterviewQuestion1?branchName=master)](https://dev.azure.com/pworthey007/Interview%20Question%201/_build/latest?definitionId=6&branchName=master)

I decided to go the NodeJS route to show my true colors when it comes to using TypeScript. The project uses tsc exclusively to type-check and transpile to javascript (dumps it to the build folder), and then Jest and webpack are downstream from there in an attempt to keep the configuration minimal.

## To grab build dependencies...

```
yarn
```

## To build & run...

```
yarn start
```

## To build & test...
```
yarn test
```

## To build & bundle...
```
yarn build
```

## Running production bundle...
```
yarn build
cd dist
node bundle.js
```