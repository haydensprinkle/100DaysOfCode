# 100DaysOfCode

A repository to store updates on my 100 Days of Code journey that will eventually be converted into a custom blog format

Day 1 (01/01/2021)

    -spent about an hour watching self-taught software engineer YouTubers to hype me up
    -created Git repo for 100 Days of Code challenge with plans to expand
    -continued work on recently started vanilla JS to-do app
        -scrapped styling due to a bug surrounding ::marker, going to focus on functionality first
        -added functionality for check button and delete button

Day 2 (01/02/2021)

    -Played around with flexbox positioning on my to-do app until I got sufficiently frustrated
    -Watched several hours of Colt Steele's updated Web Developer Bootcamp course on Udemy and completed various associated coding challenges focusing primarily on CSS fundamentals

Day 3 (01/03/2021)

    -Created a repository for projects from my Web Dev Bootcamp course on Udemy
    -Finished and pushed a race registration page for practice with forms

Day 4 (01/04/2021)

    -Learned about the different color systems used by CSS
    -Did research on the differences between various CSS frameworks including Bootstrap and Tailwind, also diving into the paradigms of object-oriented CSS and utility-first CSS
    -Practiced flexbox positioning with Flexbox Froggy
    -Contacted an open-source project (if-me.org) about joining as a contributor

Day 5 (01/05/2021)

    -Accepted as contributor for if-me.org
    -Attempted to get if-me project set up with Docker, got confused somewhere along the line and failed miserably
    -Reached out for help from the if-me dev community, waiting for a response
    -Finished the hell out of Flexbox Froggy to feel good about myself

Day 6 (01/06/2021)

    -Slow day, just worked through a chunk of freeCodeCamp's Basic JavaScript modules

Day 7 (01/07/2021)

    -Unfortunately another slow day, first shift back at work after quarantining for a couple weeks
    -Only really had time to work through some freeCodeCamp, planning to hard charge on some projects this weekend

Day 8 (01/08/2021)

    -Spent time reading through the React docs and messing around with JSX in CodePens
    -Did considerable research on JavaScript vs. TypeScript
    -Started a new small project that will allow a user to sign in to a Twitter account and post a simple text Tweet
    -Learned about communicating with Twitter's API to achieve desired functionality

Day 9 (01/09/2021)

    -Watched several videos on connecting to Twitter API
    -Learned how to implement Twitter Web Intents to direct to Twitter and post
    -Fiddled with customizing function to send data to Twitter API without Web Intents, hoping to fully implement tomorrow

Day 10 (01/10/2021)

    -Resolved issue with event handler and successfully implemented Web Intent to post Tweet
    -Didn't implement API calls, will attempt tomorrow
    -Worked through more freeCodeCamp JavaScript modules
    -Read through a hunk of Svelte documentation to understand differences of React

Day 11 (01/11/2021)

    -Started new Git repo for a simple vanilla JS weather app that talks to an API to get IP location based weather information and displays it
    -Organized project, set up basic markup, and global styling

Day 12 (01/12/2021)

    -Added code to display stats for tasks left, tasks completed, and total tasks to my to-do app, using vanilla JS DOM manipulation

Day 13 (01/13/2021)

    -Added some basic layout and styling to weather app, not responsive yet
    -Played around with location and weather API's, nothing committed or pushed yet
    -Attempted to style my to-do app and make it responsive, but to no avail just yet. Still need more practice with CSS

Day 14 (01/14/2021)

    -Did research on basic project management
    -Signed up for Trello and started a board for upcoming Weather App
    -Added cards for all tasks I can think of, planning to iterate as project progresses
    -Linked current markup elements to JS variables

Day 15 (01/15/2021)

    -Slow day, mainly just watched Colt Steele videos on AJAX and other API related topics
    -Listened to Chris Ferdinandi's podcast episode on accessibility as moral obligation

Day 16 (01/16/2021)

    -Added functionality to grab current geolocation in weather app
    -Updated Trello board accordingly

Day 17 (01/17/2021)

    -Added API call to OpenWeatherMap that returned weather data for current user location
    -Utilized proxy to run request through to avoid CORS issues
    -Extracted necessary info from returned data and assigned to variables

Day 18 (01/18/2021)

    -Linked HTML elements in weather app to data received from OpenWeatherMap API to display information dynamically

Day 19 (01/19/2021)

    -Started new project that grabs user location and displays current Covid-19 data for their county
    -Created Git repo and made initial commits to get the ball rolling
    -Got basic scaffolding set up and connected to covidactnow.org API to receive data for Sonoma County, planning to add geolocation functionality tomorrow
    -Extracted some data and injected into markup, planning to add more info sections in future

Day 20 (01/20/2021)

    -Added new sections in Covid data app for general info, infection metrics, and bed usage data for hospitals and ICU
    -Extracted data and injected into markup for new sections
    -Planning to deploy on Netlify once completed

Day 21 (01/21/2021)

    -Created Git repo to host all of the projects for my CS50A class at Santa Rosa Junior College
    -Wrote function to format date in Covid data app
    -Called toLocalString method on displayed data to make it more readable
    -Created API call to return data on all counties in U.S. including their FIPS numbers, figuring out how to use the data to implement search and autocomplete functionalities

Day 22 (01/22/2021)

    -Added sections to markup in COVID data app
    -Applied styles to entire app, including custom button, and data cards with shadows

Day 23 (01/23/2021)

    -Added some placeholder text to COVID data app search field and grabbed the input with JS
    -Figured out how to get individual data out of the array returned by the API
    -Currently figuring out how to populate my own array of objects linking counties and FIPS codes to make them searchable

Day 24 (01/24/2021)

    -Slow day, didn't get to work on any projects
    -Spent time looking up unfamiliar concepts off of Kamran Ahmed's developer roadmaps

Day 25 (01/25/2021)

    -Populated Map object with county names and FIPS codes
    -Working to figure out how to search through the object to return FIPS code based on search

Day 26 (01/26/2021)

    -Scrapped Map object and just populated an array of objects with county name, state name, and FIPS code
    -Wrote functionality for searching through array with county name and updating data accordingly
    -Wrote functionality to grab current coords, hit an API endpoint to return corresponding FIPS code, and update data accordingly
    -Replaced all instances of "Covid" with "COVID"

Day 27 (01/27/2021)

    -Slow day, did some playing around with search algorithms
    -Planning to implement bubble sort into COVID data site
