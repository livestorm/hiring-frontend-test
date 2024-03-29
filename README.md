<p align="center">
  <img width="400" height="140" src="https://svgshare.com/i/ZCX.svg">
</p>

# Livestorm Front-End Hiring Test

This test is part of our hiring process for Vue/GraphQL developers. [Apply now](https://jobs.livestorm.co/)

Be sure to read all of the instructions carefully and follow the guidelines below. This test should take you between 4 and 8 hours depending on your experience.

## Context

You just finished your first event with Livestorm! A lot of attendees watched the event: you need a tool to help you manage their profile and find potential prospects for your business.

The goal of this test is to code a small responsive Vue.js app that allows to:

- List attendees
- Filter attendees with two segments (see below)
- Display a detailed view of one attendee
- Invite someone (add a new attendee)

### Segments

The attendees list can be filtered in 3 different segments:

- `All attendees` segment: show all attendees
- `Potential prospects` segment: display only attendees with more than 50% attendance rate (a trending up icon is displayed next to the attendees name which checks this condition)
- `From Japan` segment: display only attendees from Japan

## Design

All screens are available in the [Figma source file](https://www.figma.com/file/VRtAKaTOEoobKmAKVWFp2P/Figma-front-end-test?node-id=1%3A42).

The Livestorm logo is attached in this repository.

**Important: If you haven't already, sign up for a free Figma account and sign in, so you can inspect the design.**

![livestorm-frontend-test](https://user-images.githubusercontent.com/961898/95204778-d60c4b80-07e4-11eb-818c-eb3a3516e289.png)


## API

To build this application, you'll need to connect to our GraphQL API located [here](https://livestorm-front-hiring-test.herokuapp.com/).

In you code you can use this endpoint URL:

```
https://livestorm-front-hiring-test.herokuapp.com/
```

The API is self-documented in its [playground](https://livestorm-front-hiring-test.herokuapp.com/) where you can also try it out before coding.

## What you need to do

To complete the test, **you'll need to**:

- Create the Vue project from scratch
- Write the application
- Being as close as possible to the Figma screens
- Write some unit tests (at least one)
- (Bonus) Write some integration tests or E2E tests

## Tech requirements

A few technologies/libraries **must be used** to build the app:

- Vue.js
- GraphQL
- [Tailwind CSS](https://tailwindcss.com/)
- [vue-feather](https://github.com/fengyuanchen/vue-feather) (for icons)

The goal is to show that you have a good knowledge and understand well the Vue framework with important libraries, even if it's a small app. We also chose a tech stack close to what you'll will be working on at Livestorm.

**Do not use**:

- A UI library
- A Vue CLI plugin to setup Apollo Client

## How to send your app code

When you feel you are done, send us by email: 
- A link to a **private GitHub repository** with an invite access for [@VincentGarreau](https://github.com/VincentGarreau)
- An **online demo** of the application (free version of Netlify is highly recommended 😉️)

## Tips

- **Being as close as possible to the Figma screens is very important**
- The app must be responsive! It should look good and work on both mobile and desktop screens!
- You shouldn't have to customize Tailwind, the default configuration is enough to be able to match the Figma screens
- Use native select elements
- Feel free to use Google Fonts to import Inter font
- If possible, adding a new attendee should update the Apollo cache directly instead of making the list fetch data again
- Show off your Vue and GraphQL skills! Don't hesitate to use more advanced Vue, vue-router or Apollo client features and good practices
- (Bonus) Write clear README on how the app was designed and how to run the code
- (Bonus) Describe optimization opportunities
- Got questions? Contact us! (No penalties for asking questions 😉️)
