# Trip Planner
## JS: Prompt
###### Remixed from the Flatiron School

<img src="https://s3.amazonaws.com/after-school-assets/giphy.gif" align="right" width="300px" hpsace="10">

Your job is to build a trip-planner website using both the `alert` and `prompt` functions in JavaScript. You will be coding your solution in a javascript editor such as [jsbin.com/?js,console](http://jsbin.com/?js,console)

You'll be using the `prompt` function to take in input from your user, and `alert` to relay information back to the user. 

You can store the input from the user by using a variable:

```js
var name = prompt('Please enter your name:');
```

In the example above, we've declared the variable `name` and set it equal to `prompt('Please enter your name:')`. In this line of code, the `name` variable will store whatever name the user enters in the text box that appears in the browser.

Now that we have the data from the user stored in the variable `name`, we can use that variable in our code to manipulate the data.


## Get To Work

+ **Step 1:** Your job is to take in the follow information from the user:
```
name
age
tripDestination
numberOfTravelers
typeOfTrip (relaxing, adventure, etc)
```
+ **Step 2:** Once you have all the information you need, your job is to alert the user with a sentence describing the user's vacation wishes and a promise to find them the best possible trip.

---

### BONUS 1:

+ Let's assume the cost for each traveler will be $500.  Modify the alert to include the total cost for all of the travelers.

### BONUS 2:

+ Uh-oh! The computer has a cold :( That means `n` sounds like `d`, and `m` sounds like `b`.  For example, saying _I have a nice mom_ with a cold actually sounds like _I have a dice bob_.  Use `replace` in your alert to respond with a cold.

### BONUS 3:

+ Once the user enters what kind of trip they want, see if you can figure out how to make suggestions based on what type of trip (ie: suggest a beach vacation for a relaxing trip, or hiking Machu Pichu for an adventure trip).