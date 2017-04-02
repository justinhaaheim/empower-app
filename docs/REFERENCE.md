# Reference Materials

Reference materials & notes made during the creation of this app.

### Flow
See: https://medium.com/react-native-training/getting-started-with-react-native-and-flow-d40f55746809

> Using the Flow server
> For a large project, you probably only want Flow to recheck files incrementally when they change. Flow uses a client/server architecture which allows you to start a Flow server that will run in the background and type check files as they change.

Flow installed locally with `yarn add flow-bin@0.38.0 --dev`

Edited *package.json* scripts with the following lines:

```
"flow": "node_modules/.bin/flow",
"flow-stop": "node_modules/.bin/flow stop",
```

Now the flow server can be started with `npm run flow` and stopped with `npm run flow-stop`.