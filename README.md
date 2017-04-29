# Chrome Extension with TypeScript and SASS Boilerplate
This project offers a quick and easy setup for building a Chrome extension with TypeScript and SASS. 

The project uses gulp to quickly transpile all TypeScript and SASS files into normal JavaScript and CSS files.
All the relevant files in this folder are then copied to a new folder that's ready to load into Chrome. With this you don't have to worry about including all those .ts and .scss files in your final packaged extension.

# Setup
Simply fork the repo and install with npm:

```sh
$ npm install 
```

# Usage
You can develop your extension within the *app* folder, including your ts and scss files. Once you're ready to include your unpacked extension in chrome simply run the following command:

```sh
$ gulp develop
```
This will create a new folder called *dist* which has only the relevant files included. Within Chrome you can then use the dist folder to use as an unpacked extension.
