
# Outline

React Native is advertised as a framework for developing native apps with javascript. Roughly 90% of the time, my team is able to work strictly in javascript, with only occassional trips into native code. In particular, my team has found our Android build to require more care than its iOS counterpart. This talk will look at the ways in which we have learned, sometimes the hard way, how to develop a react native app for Android, as well as my experience as a javascript developer being thrust into the native world. In particular, I will discuss our use of the react native device detection package to work through our Android style audits and ways we have worked around react native's shortcomings.

## Introduction

usual, blah blah blah, cats
Why this talk
AirBnB releases blog posts about why they aren't continuing with React Native

At Chain React, many of the companies using RN seem to have reverted back to native for Android

Setting up debugging for Android is potenitally a long and exhaustive process -- one thing many RN devs and I have complained about

iOS seems to be the RN dev team's priority, or at least the part which is getting improved and released quicker

not sure if this due to android vs iOS updates, difficulty with the actual development or RN devs' preference
example includes the
the point isn't to make JS devs native devs but allow native devs to build quickly and easily by sharing screens.

Ideally, you have at least one iOS and Android dev on the team

[https://github.com/facebook/react-native/issues/3049](https://github.com/facebook/react-native/issues/3049)

[https://medium.com/airbnb-engineering/sunsetting-react-native-1868ba28e30a](https://medium.com/airbnb-engineering/sunsetting-react-native-1868ba28e30a)

"Here’s a summary of the reasons why they are doing this, and some more reasons you probably don’t want to follow them until you are a multi-billion dollar piece of the internet." - [https://medium.com/braus-blog/airbnb-is-dropping-react-js-should-you-too-dcbff36def5c](https://medium.com/braus-blog/airbnb-is-dropping-react-js-should-you-too-dcbff36def5c)
