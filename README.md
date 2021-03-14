# Traffic Scenario Synthesis from Temporal Logic Constraints

This project aims to synthesize realistic traffic
scenarios from specifications in Temporal Logic.
This work was done as part of my thesis @ [TUM](https://in.tum.de).

## Abstract

Test case generation for autonomous vehicles has gained large scale attention in recent
years due to advances in motion planning algorithms, creating a need for verified safety
with testing scenarios of these novel approaches. To this end we present in this work a
scenario synthesis approach based on a templating system, using which we are able to
synthesize many concrete scenarios satisfying any given specification, which are then
used for verifying a motion planner.

We represent the problem of generating many concrete realizations from a single
specification as a satisfiability problem of a linear Temporal Logic formula, modelling
the behavior of every vehicle on given map data. This approach has the advantage of
implicitly coupling all vehicle interactions together, allowing for complex behavior to
emerge while specifying a minimal number of constraints on the system. Based on a
satisfying assignment to such a linear Temporal Logic formula we synthesize a scenario
by formulating it as an optimization problem, whose solution yields a concrete scenario
with exact behavior for all vehicles.

To show the applicability of our approach, we evaluate it with two templates representing a highway and urban scenario showing the range different types of behavior
generated. Therefore, we deem this approach highly relevant to the domain of falsification testing for autonomous vehicles and detail future steps for integrating it into a
closed loop testing framework.

## Getting Started

## Examples
