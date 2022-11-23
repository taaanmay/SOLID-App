# SOLID-App


## Building a demo application

```
mkdir -p  my-demo-app my-demo-app/src my-demo-app/dist
```



```
cd my-demo-app
```



```
npm init -y
```


### Use npm to install the solid-client, solid-client-authn-browser, vocab-common-rdf, and vocab-solid libraries:
```
npm install @inrupt/solid-client @inrupt/solid-client-authn-browser @inrupt/vocab-common-rdf @inrupt/vocab-solid
```

### For the browser application, install the polyfill for buffer:
```
npm install buffer
```

### Installing Webpack
[Link to documentation](https://webpack.js.org/concepts/)
```
npm install webpack webpack-cli webpack-dev-server css-loader style-loader --save-dev
```


