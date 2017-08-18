# What is Cross-platform development? 

It when you write one project and created software, can be implemented on two or more platforms.

For example, how can we make it for iOS, Android and Windows Phone?

* we can use Xamarin. But it usefull for WEB and Desktop
* there is Weex \(Vue.js way\) and Apache Cordova, Ionic, Native Script \(Angular way\). I'm not sure it can handle cross-platform case, but you can try

And in this case, React Native has huge sense, cause it's main part is React and many people don't remark this.

### How React solve cross-platform?

- WEB — just React

- Mobile apps — React + React Native 

- Desktop apps — React + Electron

You can bind common JS code to reuse in single monorepo using ReactXP \(Skype way\) or Lerna. 

`Note: if you write games - it's not your story, sorry`

### Mature matters!

Is React mature enough for WEB? Yes, the most.

Is Electron mature enough for Desktop? If you like VSCode, Atom, Slack, Discord and believe in GitHub - Yes.

Is React Native mature enough for Mobile? If you like Instagram, Skype, Airbnb, Walmart apps and belief in FaceBook - I believe Yes.

### What about Back-End?

No matter what your language is - GraphQL helps your API to be consistent.

It is a good way to go with the power of JS clients like Apollo and create tooling.

### One more aspect

TypeScript will be helpful to handle this complexity, especially in big team. 

There is alternatives, but not ECMAScript cause it's the base.

### Ready to try?

Fork simple e-shop example and mock it

* Mobile WEB - https://github.com/react-cross-platform/react-shop
* iOS and Android - https://github.com/react-cross-platform/react-native-shop
* Desktop and monorepo - sure some sunny day!



> To Be Continued...



