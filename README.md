## TypeScript

### Introduction

- TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.

## Installation

### Install Latest Node JS

### Install Latest TypeScirpt globally

```
npm install -g typescript
```

### To create a tsconfig.json, run:

```
tsc --init
```

### To set the src directory and compiled directory, edit tsconfig.json find rootDir and outDir:

```
"rootDir": "./src" // this is the ts file's directory

"outDir": "./dist" // this is compiled directory of ts files
```

### To compile ts file run:

```
tsc
```

### To run the process of compilation continuously, run:

```
tsc -w
```
