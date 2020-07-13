
Hacker News powered by [Elm](http://elm-lang.org/) + [elm-navigation](https://github.com/elm-lang/navigation) + [GraphQL](https://www.graphqlhub.com/).


## Features

* Supports display of all item types:
  [news](https://news.ycombinator.com/newest)
  [pasts](https://news.ycombinator.com/front)
  [comments](https://news.ycombinator.com/newcomments)
  [ask](https://news.ycombinator.com/ask) 
  [show](https://news.ycombinator.com/show)
  [jobs](https://news.ycombinator.com/jobs)
  [submit](https://news.ycombinator.com/submit)

It might take a few seconds to get a response from the server, so old tight! All errors are displayed on screen.

The backend api is a bit quirky in that it doesn't return all the results and has some inconsistencies in the data shown. Because of this, some of the JSON decoders are quite tricky and studying them can be a good exercise for new comers. The point of this projects is to work on a real Elm app so I'm not too worried about what gets returned by the api.

## Running

Make sure you have `create-elm-app` installed:

```
npm install -g create-elm-app
```

Run dev server with:
```
elm-app start
```

Build in `dist` folder:
```
elm-app build
```
----
Inspired by [react-hn](https://react-hn.appspot.com)