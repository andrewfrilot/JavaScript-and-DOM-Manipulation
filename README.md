# JavaScript-and-DOM-Manipulation
Creating an HTML web page to view, sort and parse data

HW #14 for Rice Data Analytics Boot Camp



Background

WAKE UP SHEEPLE! The extra-terrestrial menace has come to Earth and we here at ALIENS-R-REAL have collected all of the eye-witness reports we could to prove it! All we need to do now is put this information online for the world to see and then the matter will finally be put to rest.

There is just one tiny problem though... our collection is too large to search through manually. Even our most dedicated followers are complaining that they are having trouble locating specific reports in this mess.

That's why we are hiring you. We need you to write code that will create a table dynamically based upon a dataset we provide. We also need to allow our users to filter the table data for specific values. There's a catch though... we only use pure JavaScript, HTML, and CSS, and D3.js on our web pages. They are the only coding languages which can be trusted.

You can handle this... right? The planet Earth needs to know what we have found!


Your Task


Level 1: Automatic Table and Date Search


Create a basic HTML web page or use the index.html file provided (we recommend building your own custom page!).

Using the UFO dataset provided in the form of an array of JavaScript objects, write code that appends a table to your web page and then adds new rows of data for each UFO sighting.


Make sure you have a column for date/time, city, state, country, shape, and comment at the very least.


Add the following datum as the third entry of the data.js file:


    {
    datetime: "1/28/1996",
    city: "dallas",
    state: "tx",
    country: "us",
    shape: "star",
    durationMinutes: "5 mins.",
    comments: "Cowboys win a superbowl, that's alien!."
    }

Use a date form in your HTML document and write JavaScript code that will listen for events and search through the date/time column to find rows that match user input.
Use bootstrap to style the table with striped rows



Level 2: Multiple Search Categories (Optional)


Complete all of Level 1 criteria.
Using multiple input tags and/or select dropdowns, write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns:



date/time
city
state
country
shape





Dataset


UFO Sightings Data




Good luck!




Copyright

Data Boot Camp © 2018. All Rights Reserved.
