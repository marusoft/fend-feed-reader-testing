# Feed Reader Testing

Implement Behavior Driven Development (BDD) on a pre-existing web-based application that reads RSS feeds using Jasmine.js; JavaScript Testing Framework

[Project](https://marusoft.github.io/fend-feed-reader-testing/)

# Dependencies

1. [Required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
2. [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)
3. Udacity JavaScript Testing [course](https://www.udacity.com/course/ud549)
4. Behavior Driven Development [JavaScript Testing Framework ](https://jasmine.github.io/)
5. Unit Testing in JavaScript and Jasmine Tutorial By [Dylan Israel](https://www.youtube.com/watch?v=h2eWfvcAOTI)
6. [Jasmine Introduction](https://jasmine.github.io/2.1/introduction.html)

# Installation

```

$ git clone https://github.com/marusoft/fend-feed-reader-testing.git

```

```
$ cd fend-feed-reader-testing.git

```

* Load the index.html on a current browser like Chrome.

* Edit the code using your preferable Text Editor.


# Project Implementation

1. The template Starter was provided by [udacity](http://github.com/udacity/frontend-nanodegree-feedreader)
2. I Review the functionality of the application within my browser.
3. I Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
4. I Wrote a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
5. I Wrote a new test suite named `"The menu"`.
6. I Wrote a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
7. I wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
8. I Wrote a test suite named `"Initial Entries"`.
9. I Wrote a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
10. I wrote a test suite named `"New Feed Selection"`.
11. I Wrote a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
12. I ensure that None of the test are dependent on the results of another.
13. Callbacks was used to ensure that feeds are loaded before they are tested.

# Author

Developed by Alimi Kehinde Maruf (marusoft)