# Activity 3 - Submitting Form

In this activity, you will create a view called **"add-customer.mustache"**. The view will allow the user to enter their name and age. When the user presses the submit button the values (name and age) will be posted to **"/add-customer"** (POST) endpoint. 

Inside **"/add-customer"** route you will extract the name and age and pass it down to the "confirmation.mustache" view which will display the following message. 

The customer John with age 32 has been saved successfully

* John and 32 are just examples, you will be passing the values which you received from the FORM. 