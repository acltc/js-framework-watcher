# JavaScript Framework Watcher

We always like to keep track of the popularity of various JavaScript frameworks, and one way we do this is by using Github. Namely, we look up each framework on Github, and look at how many Stars, Watchers, and Forks each framework has. Generally, the more of these that a framework has indicates how much engagement people have with that framework. And the amount of engagement with a framework can indicate how popular it is. Of course, this is by no means a perfect measure, but it's something.

## The Exercise

However, it's really annoying to constantly check up each individual repo on Github. Currently, we keep track of these five separate frameworks:

* https://github.com/vuejs/vue
* https://github.com/angular/angular.js
* https://github.com/emberjs/ember.js/
* https://github.com/sveltejs/svelte
* https://github.com/facebook/react

We'd like for you to build a dashboard that shows many Stars, Watchers, and Forks each of these repos has. This dashboard should use some sort of graph to cleanly display this data, so we can easily see and compare the frameworks with a glance of the eye.

Your dashboard should use the [Github API](https://docs.github.com/en/rest) to pull all of the relevant data.

### Bonus

Until now, we've described how the dashboard should track three pieces of data for (Stars, Watchers, and Forks) for each JS framework. However, it would be super nice to track a fourth factor called "popularity". This isn't something that Github tracks, but would instead be based on a proprietary algorithm that you develop. That is, you'd determine based on the number of Stars, Watchers, and Forks how many "popularity points" each framework has. Again, how the algorithm determines the number of popularity points is up to you. But we'd like to see your thought process behind it.

## Submission

We're hoping that you can finish the challenge within 7 days. Please push your code to Github and deploy it to your hosting provider of choice and share the links for both when you're done.