# Minimal React Apollo SSR

[Article on Marmelab blog](https://marmelab.com/blog/2019/11/08/le-server-side-rendering-sans-framework-pas-si-dur.html)

![Fromages listing and view detail](https://raw.githubusercontent.com/zyhou/react-apollo-ssr/master/doc/fromages-to-fromage.gif)

## Features

* React 16
* Babel 7
* Webpack 4
* React Router 5
* Apollo 3 with hooks (use `getDataFromTree` for server side rendering)
* React Helmet
* Loadable component
* Emotion 10 with styled
* SSR hot reload with HMR webpack

## Installation

* `git clone git@github.com:zyhou/react-apollo-ssr.git`
* cd react-apollo-ssr
* make install
* make start
* visit `http://localhost:3000`
* bundle analyzer on `http://localhost:8888`

## API

[![Edit Fromage Graphql api](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/fromage-graphql-api-ku0n6?fontsize=14)

[GraphQl API, build with Apollo Server on 4000 port](https://ku0n6-4000.sse.codesandbox.io/)   
[REST API, build with micro on 3000 port](https://ku0n6-3000.sse.codesandbox.io/fromages)
