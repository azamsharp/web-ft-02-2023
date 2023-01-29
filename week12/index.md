# Week 12 Redux

## Day 1 
### ❗ Learning Objectives

<h4>After completing this lesson, you will be able to:</h4>

1. Manage the data ("state") in your application using the Redux library.
2. Describe your application's state using JavaScript values.
3. Write actions that describe the specific ways your application's state can change.
4. Create reducer functions that apply changes to a copy of your state.
5. Create and use a Redux store, which manages state using actions and reducer

- [Redux Flow Diagram](day1/images/redux-image.png) 
- [Redux Videos](https://www.youtube.com/playlist?list=PLDMXqpbtInQj_wOdK5et4cIS1OyLd7Zff)
- [Assignment - Hello Redux](day1/assignments/redux-intro.001.jpeg) 
- [Class Code](day1/code-downloads/hello-redux.zip)
- [Class Code - 09/13/2021](day1/code-downloads/hello-redux-new.zip)
- [Class Code - 11/28/2022](day1/code-downloads//hello-redux-11-28-2022.zip)


---
## Day 2 
### ❗ Learning Objectives
<h4>After completing this lesson, you will be able to:</h4>

1. Keep Action names in constants to avoid typos
2. Write Action Creator functions
3. Create Actions that carry additional information
4. Manage more complex state
5. Quickly copy the current state using the Object Spread operator

### Pre-Reading
- [Learning Portal - State, Actions, Reducer ](https://learn.digitalcrafts.com/immersive/lessons/full-stack-frameworks/state-actions-reducers/#learning-objectives)

#
- [Activity 1 - Actions and Creators](day2/activities/actions-and-creators.md)
- [Activity 2 - TodoList](day2/activities/todo-list.md)
- [Assignment - Books App Using Redux](day2/assignments/books-app.md)
- [Class Code](day2/code-downloads/04-20-2021-react-actions-creators.zip)
- [Class Code - 09/14/2021](day2/code-downloads/hello-redux-action-creators-types.zip)
- [Class Code - 11/29/2022](day2/code-downloads/hello-redux-11-29-2022.zip)


---
## Day 3 
### ❗ Learning Objectives
<h4>After completing this lesson, you will be able to:</h4>

1. Divide your state management among multiple Reducers
2. Use Redux's combineReducers() to provide the store with a single Reducer
3. Create Redux-specific files for organizing code for your Actions, Reducers, and Store


#
- [Activity 1 - Multiple Reducers](day3/activities/mul-red.md)
- [Assignment - Books App Using Multiple Reducers](day3/assignments/books-mul-red.md)
- [Class Code](day3/code-downloads/mul-red.zip) 
- [Class Code - 09/15/2021](day3/code-downloads/mul-reducers.zip) 
- [Class Code - 11/30/2022](day3/code-downloads//mul-red-11-30-2022.zip)
---
## Day 4 
### ❗ Learning Objectives

<h4>Why Do I Need This?:</h4>

With a plain basic Redux store, you can only do simple synchronous updates by dispatching an action. Middleware extends the store's abilities, and lets you write async logic that interacts with the store.

Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.

- [Redux Thunk](https://github.com/reduxjs/redux-thunk)
- [Redux Middleware Flow Diagram](https://redux.js.org/tutorials/essentials/part-5-async-logic)
- [Activity - Dispatching in Action Creators](day4/activities/dispatch-action-c.md)
- [Optional Assignment - Hiking App](day4/assignments/hiking.md)
- [Assignment - Books App Using Redux Thunk](day4/assignments/books-thunk.md)
- [Class Code](day4/code-downloads/hello-thunk.zip) 
- [Class Code - 09-16-2021](day4/code-downloads/books-app.zip) 
- [Class Code - 12-01-2022](day4/code-downloads/hello-thunk.zip) 

---
## Day 5 
- Review
- [Class Code](day5/code-downloads/books-app.zip) 
- [Class Code: 12-02-2022](day5/code-downloads/book-barn.zip)
