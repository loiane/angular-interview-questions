# Angular Interview Questions

A complete guideline to prepare for angular interview. Also you can use these question to upgrade your expertise in angular. 


## Table of Contents
* [Understand Your Current Level](#understand-your-current-level)
* [Know the Interviewer](#know-the-interviewer)
* [Beginners Level Question](#beginners-level)
    * [Familiarity to Basic Terminology](#familiarity-to-basic-terminology)
    * [Ability to Build Simple App](#ability-to-build-simple-app-questions)
    * [Understanding Basic Concepts](#understanding-basic-concepts-questions)
* [Intermediate Level Questions](#intermediate-level)
    * [Essential Terminology](#essential-terminology-questions)
    * [Comfortability to Build Medium Size App](#comfortability-to-build-medium-size-app-questions)
    * [Core Concepts Understandability](#core-concepts-understandability-questions)
* [Expert Level Questions](#expert-level)
    * [Performance and Edge Case Related Terminology](#performance-and-edge-case-related-terminology)
    * [Master a Large App Related](#master-a-large-app-related-questions)
    * [Rock star and Fighter for angular](#rockstar-and-fighter-for-angular-questions)
* [Coding Test Question](#coding-test)
    * [Fetch Data and Display User Profile](#fetch-data-and-display-user-profile)
    * [Persistent Todo List](#persistent-todo-list)
    * [Student Registration System](#student-registration-system)
* [Side Things Related Questions](#side-things-related-questions)
    * [rxjs](#rxjs)
    * [TypeScript](#typescript)
    * [angular-cli](#angular-cli)
    * [others](#others)


## Understand Your Current Level
The most important step to understand yourself. If needed improve your skill, strength and confidence. If you don't feel confident about anything, do a favor tjo yourself by googling and spend few minutes to read some blog or youtube videos. And then check which level you are in terms of your angular skills.

* If you can create a angular app by using angular-cli or any other seed. Also understand component, module, pipes, service, etc. you can consider yourself in the beginners level. If you don't have any clue what I am talking about, watch this [video](https://www.youtube.com/watch?v=rOr1r1rSZQ8) and become beginners level.
* If you have full functional app that is deployed somewhere and/or published code in github and you understand detail about routing module breakdown, unit test, architecture, etc., you can consider yourself in intermediate level angular developer.
* If you master in lazy loading, AOT, custom directive, deployment configuration, etc. you can put yourself in the expert level.
* Rest of the people are either angular blind or angular rock star. 


## Know the Interviewer
Do a favor to yourself. Google the interviewer. Look at his/her Linkedin profile. Check his/her youtube videos, old blog that wasn't developed in years and github profile. After your research try to put the interviewer in one of the following categories.
1. Lazy interviewer asks about terminology. Sometimes they google questions and ask you from there. They mostly ask termninology related questions. Mostly old managers ask these type of questions.
2. Modest and nicer interview wants to check whether you can get the job done. and you know stuff. For this kind of interviewer look at the How category questions
3. Smart interviewer (the guy who is a senior developer for a long time and has updated blogs and videos) wants to know that you think, you compare and analyze stuff to make consious decisions. For these type of nerdy interviewer (they would love to prove you wrong. and one important tip: don't try to prove them wrong) you should study why type of questions


Research team  member as well. Search people in the linked in by the company name and then look their profile in github. 


## Beginners Level

For the beginners level an interviewer wants to know whether this interviewee is a self learner, trainable. Hence he/she might asks question about basic terminology, your ability to build some simple app and high level understanding.  


### Familiarity to Basic Terminology
1. What are the difference between angularJS (angular 1.0) and angular2?
2. What is a component? why would you use it? 
3. What is the minimum definition of a component?
4. What is a module and what does it contains?
5. What is a service and why will you use it?
6. What is a promise? Explain it in simple words.
7. What are the  life cycle hooks for component and directives?
8. What is pipes?
9. What is a service and why would you use it?
10. What is a dumb component? and what are the benefits of dumb component?



### Ability to Build Simple App Questions
1. How do components communicate with each other?
2. How would you use http to load data from server? 
3. How do you create route in angular app?
4. How can you get current state of a route?
5. How do you create two way data binding in Angular?
6. How to load external module in angular app?
7. How you build an angular app for production?
8. Which life cycle hook will you use to unsbscribe a promise?
9. How are the services injected to your application?
10. How would you create route parameter and access it from a component?



### Understanding Basic Concepts Questions
1. Why would you use angular over some other framework like react?
2. What is the difference between an observable and a promise?
3. Tell me the difference between a component and a directive?
4. Why would you use typescript aka benefits of typescript?
5. Why different life cycle hooks is needed for a component/directive?
6. Why angular uses rxjs?
7. What is the purpose of using zone js?
8. What is the difference between ngOnInit() and constructor() of a component?
9. When will ngOnInit be called? How would you make use of ngOnInit()?





[Answers link coming soon ]


## Intermediate Level

In the intermediate level, you built medium size angular app and you played with routing, https, different built process, unit test, etc. here are the questions you could expect



### Essential Terminology Questions
1. How will you protect a route for authorized user only?
2. What is a custom pipe and how will you use it?
3. What is a structural directive?
4. What is the difference between RouterModule.forRoot() vs RouterModule.forChild()? Why is it important?
5. What is the difference between a module's forRoot() and forChild() methods and why do you need it?
6. What's the difference between dirty, touched, and pristine on a form element?
7. What is an async pipe? What kind of data can be used with async pipe?
8. What is injectable? Give me some example.
9. What is a pure pipe?
10. How will you create two way data binding in Angular?



### Comfortability to Build Medium Size App Questions
1. How do components communicate with each other?
2. How do you decide to create a new NgModule?
3. How will you inject custom header in your http call?
4. How do you identify a structural directive in html?
5. How would you select a custom component to style it?
6. How would you select all the child components' elements?
7. How would you cache an observable data?
8. How would you cache observable data?
9. How Event Emitters works in Angular?
10. How do you mock a service to inject in a unit test?



### Core Concepts Understandability Questions
1. Tell me about feature module and shared module?
2. What would you not put shared module?
3. Why angular uses decorator?
4. What is async validation and how is it done?
5. Why do you need type definitions?
6. Which components will be notified when an event is emitted?
7. Why would you export from ngModule?
8. Why is it bad if SharedModule provides a service to a lazy loaded module?
9. Can you explain the difference between ActivatedRoute and RouterState?
10. Which service will you put in the module and why?



[Answers link coming soon]



## Expert Level

You are a rockstar in angular. you can teach other. you can lead a team for angular project. you should know the answer to the following questions.

### Performance and Edge case Related Terminology
1. What is factory Component?
2. What is lazy loading and why will you use it?
3. What is Ahead of time (AOT) compilation and why will you use it?
4. What are some of the Angular Style Guide suggestions you follow on your code? Why?
5. What is wildcard state?
6. How do you put animation between two states?
7. What would be a good use for NgZone service?
8. How would you protect a component being activated through the router?
9. How would you insert an embedded view from a prepared TemplateRef?
10. What is attribute directive and why will you use it?

### Master a Large App Related Questions
1. How will you intercept http to inject header to each http call?
2. How would you create a component to display error messages throughout your application?
3. How you parallelize multiple observable call?
4. How will you put one async call before another?
5. How can you use web worker in angular app?
6. What tools would you use to find a performance issue in your code?
7. What are some ways you may improve your website's scrolling performance?
8. Explain the difference between layout, painting and compositing.
9. How can you cancel a router navigation?
10. How would you animate routing?


### Rockstar and Fighter for Angular Questions
1. When does a lazy loaded module is loaded?
2. Why angular uses url segment?
3. How will you make angular app secure?
4. how will you localize numbers currencies and dates?
5. What is the best way to use translation in you app?
6. How will you setup different environment build differently for you app?
7. How will you use scss or css preprocessing with your application?
8. How will you optimize image/svg in your angular app?
9. How would you make sure an api call that needs to be called only once but with multiple conditions. Example: if you need to get some data in multiple routes but, once you get it, you can reuse it in the routes that needs it, therefor no need to make another call to your backend apis.
10. If you need to respond to two different Observable/Subject with one callback function, how would you do it?(ex: if you need to change the url through route parameters and with prev/next buttons).




[Answers link coming soon]

## Coding Test
Sometimes interviewer would like to give a coding challenge that you have to while they are watching. Some potential employer might give you a day or two to finish a coding challenge. Here are few sample coding challenge

### Fetch Data and Display User Profile

This test has three level
1. Level 1: Create a textbox to take user input and then Fetch data from https://api.github.com/search/users?q=eric which takes a query string to search users in github. Upon retrieval display total_count and first 10 users in the search result. Detail instruction about this test is available [here](https://github.com/khan4019/github-profile-search)
2. Level 2: Convert each user profile as router link so that upon clicking on each user profile you will navigate to a route that has "login" property in the route. Pass user.login as route parameter. Create a separate component where you will read the route parameter and then fetch that user information by using this api https://api.github.com/users/eric . Please Notice that last part of the api is the user.login (the route parameter that you have passed). Finally display user image and other information in the component
3. Level 3: use any charting framework that you can find in the online and then create a simple bar chart to display number of followers of first 10 users


Focus on this coding test is to judge your ability to use services, component and observables, etc. Always remember unit test, pay attention to variable names, build, etc.

[Sample code link coming soon] 

### Persistent Todo List
Focuses on how you pass data and events between components. Also whether you are leveraging directives and understand difference between component and directives
Details coming soon

1. Level 1:  Implement a simple todo list where you can add items, mark as done
2. Level 2: Now create few categories of todo list and make it persistance in the browser
3. Level 3: Now use firebase database to make todo list persitance across multiple devices

[Sample code link coming soon]

### Student Registration System
Focuses on architecture for a large application. Your ability to think and implement module, lazy loading, asset management etc.
1. Level-1: Design a system where students can login to register different courses 
2. Level-2: Add a feature so that faculties on each courses can view how many students registered on the courses
3. Level-3: (I need a shower. will add text here after i clean up myself) 

[Sample code link coming soon]

## Side Things Related Questions

### rxjs
1. Why angular uses rxjs?
2. How would you explain Observable?
3. Why unsubscribing is important?
4. what is forkJoin, flat map, zip
5. Difference between hot and cold observables

### TypeScript
1. How to debug a typescript file?
2. How do you implement interface in typescript?
3. How would you call base class constructor from child class in typescript?
4. What is typescript language service?
5. How to declare a custom type?
6. what are the some disadvantages of typescirpt? answers [here](https://www.codeproject.com/Articles/1071285/Latest-TypeScript-Interview-Questions-for-Beginner) 

### angular-cli
1. Why would you use angular cli?
2. How would you run unit test? 
3. How do you create application to use scss
4. How to inject base href
5. How would you extract webpack config from angular cli project?


### Others
1. What is the use of codelyzer?
2. Will you use Angular Material2?
3. How would you buyild and deploy your app in multiple languages?
4. How would you set different config in different deployment server?
5. What do you know about ES6?

[Answers link coming soon]


## Contribute
Feel free to provide questions and update language
___________


Few questions are inspired by [Yonet](https://github.com/Yonet/Angular-Interview-Questions), [codeProject](https://www.codeproject.com/Articles/1169073/Angular-Interview-Questions)