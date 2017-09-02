# What is Cross-Platform Development?

It when you write project that can be implemented on two or more platforms.

<iframe
    src="https://shop.serga.name/graphiql" width="1000" 
    height="500"
</iframe>

For example, how can we make it for iOS, Android and Windows Phone?

* we can use Xamarin, but it useless for WEB and Desktop
* there are Weex (Vue.js way) and Apache Cordova, Ionic, Native Script (Angular way). I'm not sure they can handle cross-platform case, but you can try

And in this case, React Native has huge sense, cause it's main part is React and many people don't remark this.

### How React solve Cross-Platform?

* WEB — [React](https://facebook.github.io/react/)
* Mobile apps — React + [React Native](https://facebook.github.io/react-native/)
* Desktop apps — React + [Electron](https://electron.atom.io/)

You can even reuse platform's common JS code in single monorepo using

* ready solutions like [ReactXP](https://microsoft.github.io/reactxp/) ([Skype story](https://microsoft.github.io/reactxp/blog/2017/04/06/introducing-reactxp.html))
* or find your own solution using [Lerna](https://lernajs.io/)

`Note: if you write games - it's not your story, sorry`

### Mature matters!

Is React mature enough for WEB? Yes, the most.

Is Electron mature enough for Desktop? If you like VSCode, Atom, Slack or some of [385 apps](https://electron.atom.io/apps/) and believe in GitHub - Yes.

Is React Native mature enough for Mobile? Instagram, Skype, Airbnb, Walmart and [other](https://facebook.github.io/react-native/showcase.html) already use it and you can read how they did it. And if you believe in Facebook - I believe Yes.

### What about Back-End?

No matter what your programming language or platform is - [GraphQL](http://graphql.org/) helps your API to be consistent.
<br/> 
It is a comfortable way to go with the power of JS clients like [Apollo](http://dev.apollodata.com/), great tooling like [GraphiQL](https://github.com/graphql/graphiql) and many more.

### One more aspect

[TypeScript](https://www.typescriptlang.org/) — is JavaScript that scales.

* helps to handle this complexity, especially in big team
* is just ECMAScript with optional types, classes, modules and awesome tooling
* doesn't replace ECMAScript, it just helps you to write better
* there are alternatives, but not ECMAScript cause it's the base

### Ready to try?

Fork simple e-shop example and mock it

* Mobile WEB - https://github.com/react-cross-platform/react-shop
* iOS and Android - https://github.com/react-cross-platform/react-native-shop
* Desktop and monorepo with shared JS code - sure some sunny day!

> To Be Continued...
