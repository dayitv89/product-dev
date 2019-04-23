# Semantic Versioning

After building a prototype of any product we merge some updates in it.
For managing the updates a numbering system is introduced.

The numbering system is in a form of x.y.z(abc).

x=> is a MOJOR update, ie. when a software updates itself and the update is incompatible with the previous version.

y=> is MINOR update. i.e.  when you add functionality in a backwards-compatible manner(or you just add some functionality but is compatible with the last version ).

z=> PATCH version, i.e. when you make backwards-compatible bug fixes.

abc=> it is the build number added to the numbering after every team member merges its part into the main product.

### Why should we Version numbering system?

Whenever we update our software we have to give it an identification, so that when we have some issue or if we want to reference anything from the previous updates we can use this unique identification to track our update.

If we number them in an oder where we just add a number to the previous number then it would be very difficult to manage as it would give a pile of numbering after every build merge in the product.
 
And if we number in a very deep manner then for every update we have to search very deep.

So, to make a very balanced numbering system semantic versioning number system is used.

Let say react native is in version of 0.59.0. This 0 here states that it is not a stable version and is in developing stage.
59 states that it has added many functionalities starting from 1 to 59. And the last 0 is for adding bug fixes in it. In some places you will see a bracket **"()"** it is for builds i.e. whenever a team member merges its build in the react native then it is added in the previous build number in the bracket.