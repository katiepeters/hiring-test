# Hiring Test

## Summary

Create an app that loads and displays carbon intensity data from National Grid ESO's carbon intensity API. Please read the full the description before beginning.

## Detailed Requirements

Broken down into Required General, Required Functionality, Bonus, and Allowances

### Required General

* Use React.
* Use CSS (or a preprocessor if you want to get fancy).
* Add some design flair.
* Attempt at least 1 bonus item from each category (and explain your choices).
* Use best practices for source code management (commit granularity, commit message strategy, branching strategy, etc.).

### Required Functionality

#### Home (Overview) Page
* Display today's overall carbon intensity.
* Display today's carbon intensity by region (ex. as a table).
* User should be able to sort regions by carbon intensity.
* Clicking on a region should open highlights of that region in a side panel.
* Side panel should display region's carbon intensity from the past week and past month.
* Side panel should have a "Go to Region" link/button that takes the user to a region details page.

#### Region (Details) Page
* User should be able to select any time range.
* User should be able to switch to a different region.
* Display the overall carbon intensity for the selected time range.
* Display the carbon intensity for each day within the time range.

### Bonus

#### Functionality
* Use interactive graphics (ex. charts) to show data on the region page.
* Incorporate relevant data in addition to carbon intensity, either from the National Grid API or another public API.
* Make app responsive (for different screen sizes).
* Add web accessibility.
* Add localization.

#### Other
* Use TypeScript.
* Include unit tests.
* Implement a code linter and configure which rules to use (perhaps select some of your favorite and/or most-used rules?).

### Allowances

* Any reasonable React/JS/node framework to bootstrap and build your app.
* UI component libraries (but only for supplemental functionality, not to fulfill any requirements).

## Just for Kicks
One Mr. Will Buckingham would very much like you to host the running app somewhere. We will leave this up to you ;)

## API Docs

https://carbon-intensity.github.io/api-definitions/#carbon-intensity-api-v2-0-0

## Grading

* Functionality.
* Clarity and organization of code.
* Mastery of React.
* Data handling (fetching/storing/organizing - Ex. Redux?).
* User interface and creativity of design.
