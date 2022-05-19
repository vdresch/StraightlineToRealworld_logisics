# Straight line to real world

### TL;DR:

A simple quadratic equation, or even basic linear regression, can be used to predict "real world" distance and trip duration using only the straight line distance between two points. The quality of the model will depend on geographical features.

### The goal

When it comes to automate an logistics pipeline, depending on the scale or the algorithm being used, it's not always possible to query google for travel distance and time from a point A to a point B. In this cases, an approximation might work perfectly fine. This analysis is the tool to get to this approximation.

### How it's done?

First, we will get location samples from the location of study. The next step is to pair those samples and get booth the straight line distance and the "real world" travel distance and duration. With these, we will try to find a model that can predict the "real world" variables using only the straight line distance.
