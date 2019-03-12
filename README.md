# A complete list of skills and tasks to become a modern frontend developer

Based on the article [modern frontend developer in 2019](https://medium.com/tech-tajawal/modern-frontend-developer-in-2018-4c2072fa2b9c) by brother [@kamranahmedse](https://twitter.com/kamranahmedse).

I created this checklist for myself and I will be going through each of these topics till the end inshallah. So follow me or suggest me something on [Twitter👉](https://twitter.com/ruhulwebdev)

## Usage

Just study each topic and check them done. And also write articles and teach others every single thing you learn. For example after learning about Eslint, write an article saying -> what is eslint and how to set it up / how does it work?

And put the link of the article at the right of the topic. Like this -

- [x] Learn the basics --- [The basics of HTML](#) // article link

As for the tasks, complete them and put the links at the right of the task checklist

- [x] Create a webpage that uses GitHub Repositories API to fetch and show the top 10 repositories of the current week in a nice responsive format. --- [solution](#) // link of your solution or project

---

## PHASE 1: THE BASICS

### HTML

- [ ] Learn the basics
- [ ] Writing Semantic Html
- [ ] Basic SEO
- [ ] Accessibility

### CSS

- [ ] Learn the basics
- [ ] making layouts -> Floats, Positioning, Display, Box Model, CSS Grid, Flex Box
- [ ] Media Queries
- [ ] Learn CSS 3

### Javascript

- [ ] Syntax and Basics Constructs
- [ ] ES6+ and moduler Javascript
- [ ] Learn DOM manipulation
- [ ] Learn Fetch Api / ajax
- [ ] Understand hoisting, event bubbling, Scope Prototype, strict

### How the internet works

- [ ] How browsers work
- [ ] What is HTTP, how does it work?
- [ ] what is JSON and XML
- [ ] what is DNS, how does it work

> ### FCC: Responsive Web design certificate

### TASKS

- [ ] Pick and complete the [frontendmentor](https://www.frontendmentor.io/challenges) challenges --- **UI & UX**
- [ ] Create a [Pomodoro](https://en.wikipedia.org/wiki/Pomodoro_Technique) Application. You may clone and make the web version of [this application](https://electronjs.org/apps/pomotroid)
- [ ] Create a webpage that uses GitHub Repositories API to fetch and show the top 10 repositories of the current week in a nice responsive format.
- [ ] Create a simple to-do list application that allows you to add tasks, mark them complete, edit them and delete them.
- [ ] Create a simple stopwatch where the user can start, stop, pause and reset.

## PHASE 2: WRITE BETTER CSS

- [ ] package managers -> npm - yarn
- [ ] CSS architecture -> BEM
- [ ] CSS Frameworks - bootstrap
- [ ] CSS Pre-processors - SASS

### TASKS

- [ ] Add bootstrap to the phase 1 projects using npm or yarn
- [ ] convert the projects that you made in phase 1 to use BEM
- [ ] Write the CSS in SASS
- [ ] Automate the SASS to CSS conversion using npm script

## PHASE 3: RAMPING UP

This phase is going to be some time and is your step into modern frontend development. Go ahead and learn more about the JavaScript. Learn what is Webpack, understand the different concepts and why was it ever needed. Understand what is babel, why do we use it and learn how to integrate with webpack and lastly learn how to lint your code using ESLint. All of the items listed in this phase revolve around webpack.

- [ ] Babel
- [ ] npm scripts
- [ ] webpack
- [ ] eslint
- [ ] prettier

> ### FCC: JavaScript Algorithms and Data Structures

### Tasks

- [ ] Create an npm package that takes a username and gives back the list of links found on the social networks (if they exist). It should be usable in the browser, bundle it with webpack, use babel to transpile it and use ESLint for linting.
- [ ] Create a simple to-do list application, use SASS for the CSS, add bootstrap for styles, use BEM, transpile JavaScript using babel, bundle it with webpack, create optimized production build and deploy it on Github Pages.

## PHASE 4: MASTER A FRAMEWORK

### ReactJS

- [ ] Understand React Fundamentals

#### State Management

- [ ] Redux
- [ ] Redux thunk
- [ ] Redux saga
- [ ] rematch
- [ ] reselect

### Type-checkers

- [ ] proptypes

### Routing

- [ ] React-router

### API clients

- [ ] fetch(native)

### Form helpers

- [ ] redux-form
- [ ] formik

### Utility libraries

- [ ] lodash
- [ ] Moment
- [ ] classnames

### i18n

- [ ] React Intl

> ### FCC: Frontend libraries certification

Once you have learned ReactJS, go ahead and read about Progressive web apps. Now that you know frontend frameworks, it shouldn’t be that difficult for you. Have a look at the [PWA checklist](https://developers.google.com/web/progressive-web-apps/checklist), read about service workers, measuring performance, using lighthouse and look at the different browser APIs that you can use to your advantage e.g. Storage, Location, Notifications, Device Orientation, and Payments. Also read about [RAIL model](https://developers.google.com/web/fundamentals/performance/prpl-pattern/) and [PRPL pattern](https://developers.google.com/web/fundamentals/performance/prpl-pattern/).

### Read

- [ ] About Progressive web apps
- [ ] Have a look at the [PWA checklist](https://developers.google.com/web/progressive-web-apps/checklist)
- [ ] About service workers
- [ ] Using lighthouse
- [ ] Look at the different browser APIs that you can use to your advantage e.g. Storage, Location, Notifications, Device Orientation, and Payments
- [ ] About [RAIL model](https://developers.google.com/web/fundamentals/performance/prpl-pattern/) and [PRPL pattern](https://developers.google.com/web/fundamentals/performance/prpl-pattern/)

> ### Once you are done with this, you should be able to call yourself a modern frontend developer. Make sure to practice what you learn. Here is the list of tasks that you may pick from if you are looking for ideas.

### Tasks

- [ ] Create a simple application that lets you pick a few hashtags and uses [Twitter's search API](https://developer.twitter.com/en/docs/tweets/search/api-reference/get-search-tweets.html) to fetch and show you the most recent tweets for those hashtags in a trello like a layout grid. Try to pin the hashtags so that when the user refreshes the page, it remembers the hashtags that you picked. Use react router and add about pages.
- [ ] Create a Pomodoro application similar to [this one](https://splode.github.io/pomotroid/) that lets the users configure the duration for work and breaks, shows notifications and plays a sound whenever work or break has ended/started.
- [ ] Re-create the GitHub [trending page](https://github.com/trending) using React and allow filtering using language and dates just like GitHub. You may add any libraries for dates.

## Phase 5: Automated Testing

Learning to write automated tests for your applications is going to save you a lot of headache in the future and is going to put you in a better position when looking for a job.

- [ ] Learn what are the different types of testing, different concepts such as mocking, stubs etc.
- [ ] Go ahead and learn Jest, Enzyme, and Cypress in a respective manner
- [ ] Learn to calculate the test coverage

### Tasks

- [ ] For the tasks, go ahead and write unit, integration and functional tests for the application(s) that you created in Phase 4 above.

## Phase 6:  Static Type Checkers

Type checkers allow you to make your code more maintainable as it grows, increases your agility when doing refactoring, provide better support in the IDEs and are the best form of documentation that you can have. There are mainly Flow and TypeScript in this domain. However, there is more push towards TypeScript and I would recommend you to go with that.

- [ ] Typescript

### Tasks

- [ ] Go ahead and convert any of your existing JavaScript applications to use TypeScript

## Phase 7:  Server-Side Rendering & Static Site Generator

Server rendered applications allow achieving better performance and improved SEO as compared to the client rendered applications. Although not a requirement it would definitely help you in crafting better frontend applications. There are different options available, based on the frontend framework of your choice; but if you picked React.js then you should go with Next.js which makes SSR a breeze.

- [ ] Next.js
- [ ] GatsbyJS

### Tasks

- [ ] Convert any applications that you made above to be rendered on the server side using Next.js
- [ ] Create your personal blog and import all your posts

## Go Beyond

Everything shown in this phase is optional and is not really required for you but if you would like to try them out, go ahead and have a look.

- [ ] Learn about Node & Express a little

### Tasks

- [ ] Create a simple crud application using MERN stack

### Create a portfolio website and put all these project in there or just put your fork of this repo in there

Where to get the design? Because you are a frontend developer not a designer and people say you must have a great looking portfolio site to attract and showcase what you know to potential clients and employers. I have no idea on this one🤷‍.

---

## Please send a PR if you think something's missing or you have an anwer
