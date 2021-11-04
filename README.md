# bunk-full-stack-test

![](https://nypost.com/wp-content/uploads/sites/2/2020/09/ELON.SPACEX.web_.jpg?quality=80&strip=all)

Thank you for taking the time to do our technical test. It consists of two parts:

* [A coding test](#coding-test)
* [A few technical questions](#technical-questions)

To avoid bounced emails please submit your results by uploading the relevant ZIP file to a shared Google Drive folder or public repository.

## Coding Test

There is an open source SpaceX API [https://github.com/r-spacex/SpaceX-API/tree/master/docs#rspacex-api-docs](https://github.com/r-spacex/SpaceX-API/tree/master/docs#rspacex-api-docs) where you can get all the launch details, crew, payloads etc for the rockets.

Please use at least these 3 endpoints (fetch server-side only):

```
// Get upcoming launch details
https://api.spacexdata.com/v4/launches/upcoming

// Get crew names
https://api.spacexdata.com/v4/crew/{{id}}

// Get rocket
https://api.spacexdata.com/v4/rockets/{{id}}

```

The task is to create an application that presents the upcoming launches. We wanna get hyped so a countdown for each launch is essential and we want to know each crew member and the rocket that's launching.  


### Languages

- JavaScript - TypeScript
- Angular 8+ & RxJS (preferred) 
- Node 10+ 



### Task requirements

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met. However, we understand people have busy lives and would guide you to spend no more than 2-3 hours on a submission. We also take into consideration the [Answers to technical questions.md](#technical-questions) file and what you would like to have added if you had more time. You should look at this as the complete solution, it's much quicker to explain what you would like to have done than code it.

- Your code should compile and run in one step
- You **must** include tests

### User Stories

Given I am a **user running the application**<br/> When I **land on the page**<br/> Then I want to see **all the upcoming launches** in cards<br/>

Given I am a **user running the application**
<br/> When I **click on a launch**<br/> Then I want to see a **detail view of a launch**<br/> And I want to see **the rocket and crew in more detail** (pick any details)


#### Acceptance criteria

Each launch card has a:

1. Media image
2. Flight number
3. Rocket name
4. Text based countdown timer from time to launch.

Each launch detail view has at least:

1. Crew member details
2. Rocket details


# Technical questions

Please answer the following questions in a markdown file called `Answers to technical questions.md`.

1. How long did you spend on the coding test? What would you add to your solution if you had more time? If you didn't spend much time on the coding test then use this as an opportunity to explain what you would add.
2. What was the most useful feature that was added to the latest version of your chosen language? Please include a snippet of code that shows how you've used it.
3. How would you track down a performance issue in production? Have you ever had to do this?


#### Thanks for your time, we look forward to hearing from you!
