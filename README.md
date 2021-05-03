# Robot Army React Router App

You will practice using React Router to build a multi-page, front-end UI. 

## Demo

You can see a [demo of the app](https://robot-gallery.herokuapp.com/). It is hosted on Heroku, so it may take a few refreshes to wake up the server. 

Play around with the app, you should be able to filter a robort by type using the `<select>` input. You should also be able to click on a robot's avatar image to see the profile on that robot. **Notice how the URL changes as you click on different bots**. This is an important feature you **NEED** to have in your app.

## API

You will need to make a fetch call to `https://bot-battler-api.herokuapp.com/api/v1/bots` to get robot data.  

## Starter Code

There are _a lot_ of hints that the starter code gives you. Although you are allowed to change up the starter code however you'd like, it will be easiest to let the existing code guide you into building out this app. 

Note that not all the components in the code are rendered on the DOM, but you should explore _and use_ these components!

## React Router

You will need to `npm install react-router-dom` in order to build out this app. Read the [React Router Documentation](https://reactrouter.com/web/guides/quick-start) to review all the possible things you can import.

## User Testing Your App

It's important to test that you app can handle **both** user navigation as well as clients requesting specific URLs. 

> Go to the `/` page of your app and make sure you can click on your bots to navigate to the single Bot Show Page.

> Go to the `/robots/:id` page of your app and make sure you can navigate back to the Bots Page by clicking the Back button.

> **BONUS**: What happens if a user types in a URL of `/robots/1000000` or some robot that doesn't exist??? How could you render a 404 Page? Or many you would redirect them to the Bots Page?

## Submitting Your Assignment

When you are finished, push your code up to Github and submit on Canvas.
