# Activity 1 - Multiple Reducers 

In this activity, you are doing to learn how to create multiple reducers. 

Create an app, which consists of a "Increment" button. This button will increment the value of the counter. The value is maintained in the global Redux state. 

On the same page create another button, which will display a random image to the user. Each time a user clicks on the button a new random image URL is added to the "images" global state property and then displayed on the screen. The random image is added to the `randomImages` array in global state.  

Your global state may look like this: 

```js
const initialState = {
    count: 0, 
    randomImages: []
}
```

To produce the random image you can use the following service: 

https://picsum.photos/

The random image URL is shown below: 

https://picsum.photos/200/300/

