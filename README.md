# bunk-full-stack-test

![](https://nypost.com/wp-content/uploads/sites/2/2020/09/ELON.SPACEX.web_.jpg?quality=80&strip=all)


To avoid bounced emails please submit your results by uploading the relevant ZIP file to a shared Google Drive folder or public repository.

## Coding Test

There is an open source SpaceX API [https://github.com/r-spacex/SpaceX-API/tree/master/docs#rspacex-api-docs](https://github.com/r-spacex/SpaceX-API/tree/master/docs#rspacex-api-docs) where you can get all the launch details, crew, payloads etc for the rockets.

Please use at least these 3 endpoints (fetch server-side only):

```
// Get upcoming launch details
https://api.spacexdata.com/v4/launches/upcoming

// Get crew names (if there are any - most launches are unmanned)
https://api.spacexdata.com/v4/crew/{{id}}

// Get rocket
https://api.spacexdata.com/v4/rockets/{{id}}

```

The task is to create an application that presents the upcoming launches. The app should consist of a node backend for consuming the API, and an Angular frontend for displaying the data in some cards. We wanna get hyped so a countdown for each launch is essential and we want to know each crew member and the rocket that's launching.  


### Technologies

- TypeScript
- Angular
- Node


### Task requirements

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.


### User Stories

Given I am a **user running the application**<br/> When I **land on the page**<br/> Then I want to see **all the upcoming launches** in cards<br/>

Given I am a **user running the application**
<br/> When I **click on a launch**<br/> Then I want to see a **detail view of a launch**<br/> And I want to see **the rocket and crew in more detail** (pick any details)


### Acceptance criteria

Each launch card has a:

1. Media image
2. Flight number
3. Rocket name
4. Text based countdown timer from time to launch.

Each launch detail view has at least:

1. Crew member details
2. Rocket details

Fetch all data from the api server side

#### Thanks for your time, we look forward to hearing from you!
