# Hiring Test

## Summary

Create an app that loads buildings and its sensor readings into and Overview Page.  
Please read full description before beginning.

## Detailed Requirements

Broken down into Required General / Functionality, Bonus, and Allowances

### Required General

* Must be written in React
* Some styling using CSS
* Git commits as you build w/ clear message
* Prefer REST, however GraphQL is supported
* Overall design is up to the developer
* Attempting atleast some of the bonus items

### Required Functionality

* Fetch a list of buildings
* Display a table of buildings with their summary data showcased
* As much of the data returned should be used to build the interface
* Option to filter the list of buildings by `active` state, this should be done in the api call
* Columns should be appropriately sortable (or not)
* Clicking a building should take me to a different page where we showcase the individual building in a different form.

### Bonus

(See Grading section for Bonus items outside of functionality)

* Search by `building.name` (via API)
* Pagination (via API; results per page can be as low as 1 and 2 to prove functionality)
* Building page should load and display a chart (developers choice of charting library) showing the readings for one type of sensor
* Ability to deep link to the building view and load just one buildings data to display.

### Allowances

* Use any reasonable React/JS/node framework to bootstrap and build your app
* Use of a UI Component Library (as long as it does not just do the functional requirements for you)

## API

(TBD)

## Grading

* Functionality
* Clarity and Organization of Code
* User Interface / Creativity of Design
* Bonus:
  * TypeScript
  * Styling Thoroughness / Organization
  * Code passing a standard linting suite
  * Unit Tests
  * App Hosted/Deployed
  * Mobile Responsive
  * High Google Lighthouse Scores
  * Web Accessibility Considerations
