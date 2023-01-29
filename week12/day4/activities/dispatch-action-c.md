
# Activity 1 - Dispatching in Action Creators

In this activity, you are going to fetch `posts` from the following API and then display it on the screen. 

**API**
https://jsonplaceholder.typicode.com/posts

You will perform the fetch inside the `action creator` and then dispatch an action passing the posts to Redux global state, where it will be persisted in the posts array. 

```js
const initialState = {
    posts: [] 
}
```

Finally, you will display all the posts in the PostList component. 