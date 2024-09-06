# Procedural Chemicals
 Procedural creation and reaction of new elements/materials/chemicals.
## How it works
 When a chemical is created it gets 6 variables from its seed. [a, a2, canReactWithSameElement, state, color, weight]

 a and a2 are used in the reaction test

 canReactWithSameElement determines if it will even process reacting with it's own seed/element type

 state determines if its a [gas, liquid, powder]

 color is color

 weight is mainly for liquids to see what sinks
 
 When 2 chemicals collied their a1 and a2 values are run through the reaction function if they react then their ids are hashed and an element's new variables are calculated and it's changed into a new element.