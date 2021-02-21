# Exercise One

This is the first exercise in the Redux chapter. Here covers the fundamentals of the Redux tool.

<br>


## Lesson Challenge #1

[Q1] **What are the advantages of using Redux?**

[A1] 
- Predicatable state updates make it easier to understand how the data flow works in the application.
- The use of "pure" reducer functions makes logic easier to test.
- Centralizing the state makes it easier to implement things like logging changes to the data, or persisting data between page refreshes.

[Q2] **Describe the 3 principles Redux follows.**

[A2] 
1. Single Source of Truth - Redux uses only one store for all its application state. Since all state resides in one place, Redux calls this the single source of truth.

2. State is Read-Only - According to the Redux docs, "The only way to mutate the state is to emit an action, an object describing what happened." This means the application cannot modify the state directly. Instead, "actions" are dispatched to express an intent to change the state in the store.

3. Changes are made with Pure Functions - Reducers are functions that you write which handle dispatched actions and can actually change the state.

<br>

## Lesson Challenge #2

[Q] Take a look at the `index.html` file and fix the 8 bugs.

[A] This branch contains the bugs fixed file. [Demo](https://reactnd-redux-exercise-one.netlify.app/ "Exercie One")
