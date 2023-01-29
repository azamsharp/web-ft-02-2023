# Evaluation 

1. Go to jsfiddle.net 
2. Type the following code in the HTML area

![alt text](/images/ev-html.png)

3. Type the following in the JavaScript area 

![alt text](/images/ev-js.png)

4. Paste the following in the JavaScript area 

``` js
function uuidv4() {
  return 'DCxxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx'.replace(/[xy]/g, function(c) {
    var r = Math.random() * 16 | 0, v = c == 'x' ? r : (r & 0x3 | 0x8);
    return v.toString(16);
  });
}
```

5. Press the Run button 
6. Click on the **Generate** button 
7. Submit the special code displayed on the screen 