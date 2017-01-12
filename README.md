# node-prender-example
A node-prender example setup

# Try
## Setup
```
git clone https://github.com/aularon/node-prender-example
cd node-prender-example/
npm install # installs package.json dependencies prender-babel, prender-less & prender-pug
npm install -g prender
```
## Development (`serv` mode)
Runs a development server that compiles files on request
```
prender public/
```
## Compiling (`dist` mode)
Transforms files from source directory to target directory
```
mkdir dist
prender public/ dist/
```
