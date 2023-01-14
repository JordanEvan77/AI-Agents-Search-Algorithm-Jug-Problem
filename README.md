# AI-Agents-Search-Algorithm-Jug-Problem
The common Jug problem (Empty, Fill and Pour) using search algorithms to train an AI.



The "water jug" problem can be stated as follows:

you have a jug with a capacity of 7 liters of water, and a jug with a capacity of 3 liters of water,
you have a water source that will fill either jug to capacity
you have a drain that can be used to empty either jug
The available actions are

fill either jug from the water source
empty either jug into the drain
pour some water from a source jug into a destination jug. The amount actually poured depends on the water level of the source jug and the capacity of the destination jug. For example
if you tried to pour the 3-capacity jug containing 2 liters into the 7-capacity jug containing 6 liters, the 3-capacity jug would contain 1 and the 7-capacity jug would contain 7
if you tried to pour the 7-capacity jug containing 3 liters into the 3-capacity jug containing 0 liters, the 3-capacity jug would contain 3 liters and the 7-capacity jug would contain 0 liters
It costs 5 to fill either jug regardless of how much water is required. It costs 3 to empty either jug regardless of how much water is emptied. It costs 1 to transfer water from one jug to another, regardless of how much water is transferred.

A problem consists of

Initial -- the initial contents of both jugs
Goal -- a desired fill level for each jug
So for example, a problem is to find the lowest cost sequence of actions that starts with both jugs empty and results in 0 liters in the 3-liter jug and 3 liters in the 5-liter jug
