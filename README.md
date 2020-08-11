## 05 Work Day Scheduler
![Project license badge](https://img.shields.io/badge/license-MIT-brightgreen)

Create a simple calendar application that allows the user to save events for each hour of the day. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.


# Table of Contents
  * [User Story](#User-Story)
  * [Installation](#Installation)
  * [Usage](#Usage)
  * [Contributing](#Contributing)
  * [Questions](#Questions)

## User Story
```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Installation
```
i. Fork the Github repository.
ii. Clone the forked repo into your local machine
iii. open index.html in browser
```

## USAGE

Notable Technologies Used:
- Moment.js

Using Moment.js, I was able to grab the current date/time/hour to be used and displayed.
Using a for loops, I created the necessary HTML elements for each time block. The for loop also added the necessary classes/ids needed to target/select, as well as set and get unique Local Storage variables.

Using if/else statements, the current hour was compared to the hour value of each time-block and were assigned classes of past/present/future. Depending on past/present/future, CSS would update accordingly.

Clicking the save button will automatically save the currently inputted value of each timeblock to its unique storage value.

## Contributing
[Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.md)

## License 
[MIT](https://github.com/jonnikim/05WorkDayScheduler/blob/master/LICENSE) | Copyright © 2020 Jonathan Kim

## Questions  
Have questions? Contact me at:
##### Email: jonathan213kim@gmail.com
##### Github: https://github.com/jonnikim
##### Porftolio: https://dry-springs-76393.herokuapp.com/
##### LinkedIn: https://www.linkedin.com/in/jonathan-h-kim/
