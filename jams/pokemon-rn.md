
### Details:

Name of the app TBD so far!

**Outcome**: Build a app that combines Pokemon + Tamagotchi + exercise! Start out with a starter Pokemon, start walking, convert your steps into Pokedollars, and use that to take care of your Pokemon and evolve them! Oh, and collect more Pokemon as you walk.

**Requirements**: Understanding of React and concepts associated with it, including `fetch`. No prior experience with React Native, Expo, native bundling, etc. - those are all things we talk about in this jam!

**Language Used**: React Native

**Customization Opportunity**: Everything and anything. Examples: Add goal setting! Add charts with a library like [`react-native-svg`](https://github.com/software-mansion/react-native-svg)! Use another API instead of Pokemon! Customize the styling! Extend support for other kinds of exercise! Add a shop where you can buy boosts! Add a battle scenario feature, like the actual Pokemon games! And the list goes on.

**Platform Limitations**: This project works in browsers by using [Expo Snack](https://snack.expo.dev/), but the issue is that the pedometer sensor doesn't work :( No problem! We'll add two options: if you only have access to a computer, you'll build a clicker game (I guess you're exercising your fingers or something), but if you have access to a phone, you'll build out the exercise feature.

**Time Estimation**: 5 hours, divided into five separate jams. At the each of jam, you'll come out with a already working app and build on top of that in the next one.

### Breakdown:

* **Part One: Pedometer**: Introduction to React Native and what Expo is! We'll walk through setting it up and how React Native works, comparing it to React. By the end, you'll either have a pedometer app or a clicker app depending on whether or not you have access to an actual phone.
* **Part Two: Navigation**: We'll introduce navigation in this one and how to use `@react-native/navigation`! By the end, we'll have three screens: one where you can choose a starter Pokemon from a hardcoded list, the initial one from Part One, and one where you can see stats about your Pokemon!
* **Part Three: Currency!**: Now it's actually time to take care of our Pokemon! We'll work on converting steps into our virtual Pokedollars, and updating our Pokemon's energy and hunger with these Pokedollars.
* **Part Four: PokeAPI**: By part four, we can take care of one Pokemon, and that happens to be our starter Pokemon, which is hardcoded in. What if we want to evolve it when it reaches a certain level? Here, we'll introduce fetching in React Native (exactly the same as fetching in React) using [PokeAPI](https://pokeapi.co/). By the end, we'll be able to evolve our starter Pokemon into its next evolution stage when it reaches a certain XP.
* **Part Five: Your turn!**: We have one last feature we're going to implement: collecting more Pokemon! Except it's your turn to write the code. Broken down into a section of challenges with hints, you'll create a screen to search and add Pokemon to your list of Pokemon so we can have more than one.

Boom! There you have it! Now you can collect Pokemon to your heart's content while exercising. (Or clicking. It's still exercising on a minor scale.)

* **Why should HCers care about this project?** You get to learn React Native! Plus you come out with a fun hacky project you can actually use.

* **General outline of a club meet doing the Jam**:
    * **5 minutes**: setup, get on Expo Snack or local dev environment
    * **50 minutes**: going through the jam, debugging, testing it out
    * **5 minutes** (extended to ten depending on jam part #): customize, or show and tell

* **What club members will walk away with**: Knowledge of React Native! They can now build their own apps with React Native for both iOS and Android.

* **What makes this workshop fun or interesting for club members?**: Who doesn't like collecting Pokemon? More importantly, club members come out with a project they can actually use at home and share with people. (For example, if I were to run this club at my school, we wouldn't be able to use our phones because the school blocks cell signals, but I imagine club members would be excited enough to see if, you know, the pedometer function actually worked, enough to code on their own at home.)

* **What platforms will be supported (i.e. MacOS, Windows, Chromebook, mobile, browser, etc.)?**: All platforms. Access to a phone means you get more out of this jam, but it's not required per se.

* **How will you allow club leaders to add their own project to the Jam presentation (giving them a sense of ownership over the meeting)?**: Show and tell where people demo extra things they added, and help other clubbers add that feature to their version. Plus the fact that they get to actually use *use* the app lets them feel like they own what they've built. 
