# Feed Reader Testing with Jasmine

This is a basic feed reader that has some Jasmine tests for basic functionality. The tests cover:

* If the various feeds are defined and not empty
* If the feeds have defined urls and not empty
* if the feeds have defined names and are not empty
* If the menu sidebar is hidden by default and if it shows when the menu icon is clicked
* If there is at least one entry in the .feed div after loadFeeds() runs
* If the feed selection changes the content of the feeds, looping over each possible option

# Running the Application

Just open index.html in a browser to see the results of the jasmine tests.