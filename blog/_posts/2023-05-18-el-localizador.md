---
layout: post
title: El-Localizador: Rudimentary Yelp
---
![El Localizador](https://github.com/dylan-sh/el-localizador/assets/50163127/17750565-1791-4fd0-bff5-e2ca25c828e0)


El Localizador (*The Locator*) was a project that I created in my senior year of high school. The goal was to create a program using Java and Java Swing that allowed the user to see all of the businesses within a radius they set, of a category that they select, and sort by either distance or rating. The rating was something that they would set themselves, it wasn't advanced enough to import Google reviews or Yelp or anything. They could rate it out of 5 stars and write a short description of their experience should they ever visit it again. It would also show them the location of the establishment, but wouldn't navigate or anything.

It geolocated the user's location by figuring out the user's IP address and calling an API (which still works, and I hardcoded in the API key so *please* don't steal it for your own ripoff of a ripoff of Yelp!) that returned the general locaiton of the user. Obviously, this isn't ideal, as for me it says I'm in Louisiana despite being in Texas, but it was for educational purposes anyway so that doesn't matter too much. An interesting note is that it requests user consent before proceeding, a very progressive feature for late 2018.

El Localizador is spoken of in the past tense, because unfortunately the fact that it was written in Java 10 and uses Java Swing (successed by JavaFX) has caused it to be a bit buggy and difficult to get working. I attempted to revive it recently by installing the OpenJDK version of Java 10 and integrating Maven to fix an API JSON bug, but unfortunately it still does not load properly. I'm sure with enough time and effort I could bring it back, but given the time and effort that would take I unfortunately feel the sun has set on that gray and turqouise backdrop forever.

Below is the original class diagram for the project:

![class diagram](https://github.com/dylan-sh/el-localizador/assets/50163127/74201794-8207-4b58-8399-346b19eed714)
