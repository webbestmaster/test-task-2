# Test task 2

[![Github CI](https://github.com/webbestmaster/test-task-2/actions/workflows/github-ci.yml/badge.svg)](https://github.com/webbestmaster/test-task-2/actions/workflows/github-ci.yml)

Live demo - https://webbestmaster.github.io/test-task-2

Repository link - https://github.com/webbestmaster/test-task-2

## Installation

1. install nodejs v18.x (or higher) for your platform
2. go to project's directory
3. run `npm i`


## Dev mode

1. make installation
2. go to project's directory
3. run `npm run start`
4. open http://localhost:9090/


## Description

For developers:

1 - In developer mode, the request to the server is made twice (useEffect is called twice), this is because I use `<StrictMode>`, the link to the documentation is https://legacy.reactjs.org/docs/strict-mode.html. In the assembled project, there is no such problem.

2 - I connected localization to the project because I think that the lines of "human text" in the code are bad practice.

3 - I did not use debounce or throttle, because in our example everything works fine without them, you can check it on the performance tab in chrome dev tool.

4 - I did not connect redux because our project is too small for it.

5 - I wrote tests that check the structure of the server response, I think, for our project it is very important to have the correct response from the server.

6 - Coverage by typescript's types - 100%.

7 - _The last and probably the most important point in this document: my decisions, ideas, implementations, coding style and so on can (and will) differ from the one you use in the team, and, of course, if we work together, then I will write the code in the same way as the team._

In any case, I'm waiting for your opinion. Have a nice day :)


## License

See [license](license).

---

# Requirements

## Home Assignment - TV Series Search Frontend
The assignment is to create a web application which allows the user to search for information about TV Series, using the TV maze API (https://www.tvmaze.com/api). It should show the search results in a list and allow the user to see more detailed information in another view.

The TV maze API has a free public API which can be used for this assignment.

The requirements are quite open, however the site must be completely responsive and work on both mobile and desktop. Additionally, the web application should give the end user feedback concerning errors or very slow internet connection. It has to work on the latest versions of Chrome. The site should have two views, one for the detailed information about the series and one for the search and result. It should be possible to send a direct link to the detailed view, so it can not be completely dependent on the search view. The repository must contain documentation about how to run the application in a simple manner.

The web application should be written using ReactJS. Libraries requesting the API, such as Axios are allowed but not some TV maze API client libraries. CSS libraries and frameworks are also Ok to use.

The expected time frame for this home assignment is considered to be around ~5 hours, please document in the README.md if there were time constraints limiting your work and what you would’ve done if you’d had more time. Feel free to spend more time on the assignment if you like to.

The assignment will be judged according to the code’s readability and structure. We prefer clean, self-documenting code which is thoroughly tested. It should be written using Typescript, our preferred programming language for such an assignment.

## Delivery

Don’t hesitate to contact us concerning the assignment. The code should be delivered to us as a zip file or via git read permissions.
