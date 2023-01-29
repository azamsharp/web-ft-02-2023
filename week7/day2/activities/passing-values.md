# Activity 2 - Passing Values to the Page

In this activity you will allow the user to pass their name in the URL as shown below: 

```/customers/John```

You will extract John using the route parameters approach discussed earlier and then pass it down to the customers view. Here is the outline: 

```
app.get('/customers/:name',(req,res) => {

    // access the :name parameter 

   // render the customers view and pass down the name 

   res.render('customers',here you will pass the name to the customers view) 

})
```