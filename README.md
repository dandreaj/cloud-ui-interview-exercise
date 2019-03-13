## Cloud UI Take Home Exercise

As the next step in the interview process, we’d like you to complete a take home exercise.

Let's assume `deployment.json` is the API response you want to present to the user of a cloud service. Every day, we work with data similar to what you'll find in the provided JSON file. It consists of an Elasticsearch deployment. A deployment is one or more products from the Elastic Stack configured to work together, each one in its own node. Each deployment has a number of properties such as: is the deployment healthy, does it have Kibana enabled, and so on.

The task is to create a dashboard presenting the data in the provided JSON in a clear and intuitive manner that allows a user to see everything that is relevant to them, but without overwhelming them either.


You can use this project to set up the environment quickly.
We recommend spending 3-4 hours on this exercise, but if you need more time, please let us know.

You can install the project with

```
yarn
```

and start it with

```
yarn start
```

## About this repo

This app uses [React](https://reactjs.org/) and was generated using [create-react-app](https://github.com/facebook/create-react-app). This is meant to give you a head start so you don't have to worry about app setup. We leveraged [React Router](https://github.com/ReactTraining/react-router) so you can easily setup additional routes if you'd like. Feel free to do what you wish with the code from here!

We've also included the [Elastic UI Framework](https://github.com/elastic/eui) (EUI) for you to use.  The [EUI living style guide](https://elastic.github.io/eui/#/) provides plenty of examples for you to reference. 
