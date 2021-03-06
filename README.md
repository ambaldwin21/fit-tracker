#Earn Your Cheat

A mobile-first app designed to track your daily health and fitness choices to earn points towards a cheat food of your choice.

**Here's a video walkthrough:** https://youtu.be/irtDt3QiQyE

**Check it out here:** http://earnyourcheat.herokuapp.com/

##Features

1. The home page gives you a brief introduction and allows you to sign up/log in via the form or externally using Facebook.

![screen shot 2016-12-06 at 11 31 50 am](https://cloud.githubusercontent.com/assets/18018191/20938511/a33b20aa-bba8-11e6-9484-babdf406b4ca.png)

2. If you are a first-time user, you will be redirected to the levels page where you can choose your difficulty. Depending on what you choose, you will be given varying number of points to start.

![screen shot 2016-12-06 at 11 32 24 am](https://cloud.githubusercontent.com/assets/18018191/20938527/b091e81a-bba8-11e6-98da-548e4563baeb.png)

3. You will then be redirected to your main page where you'll see your total points.

![screen shot 2016-12-06 at 11 32 44 am](https://cloud.githubusercontent.com/assets/18018191/20938571/d0b9cce8-bba8-11e6-920e-a84160b68159.png)

4. Here you can use the switches to record whether you ate healthy and drank enough water for each part of the day. The app automatically determines time of day, but if you forget to log your progress, you can always go back and record it.
5. Hitting the Get Your Points button will increment your points for eating healthy and drinking enough water.
6. Clicking on the activities button will redirect to the activities page where you can click on each image and log the distance and time for each.
7. Upon submitting that form, you'll be redirected to the main page where your points will update based on what activity information you added.
8. When you get to 400 points for that day, you will receive some bonus points which gives you incentive to be healthy and active every day.
9. Clicking on the blue total points will redirect you to a page with three levels of cheat food items pulled from our API. The point-value of the cheat item will be deducted from your total number of points if you choose one.

**Note:** There are also admin privileges where an admin can delete users whose points are in the negative.

##Technologies

For Facebook's external authorization and log in/sign up, we used Facebook's SDK.
To populate the cheat items, we used the Nutritionix API.
The app uses a Materialize framework, handlebars templating and Express.js to query our Postgres database.
