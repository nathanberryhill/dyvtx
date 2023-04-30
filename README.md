# dyvtx
did you vote, texas?

dyvtx is a Vote Checker Tool for those who voted in the general election in 2020 and 2022 in the state of Texas. You can search by your Voter ID Number or First/Last Name and County.

dyvtx is written in **pure** HTML, CSS, and JavaScript - all without a database! Voter information stored here was obtained from the Texas Secretary of State.

### Why no database?
While a database for this purpose would be nice, there are several considerations to be made:
- Cost. SQLiteDB is free, but others are not. Also, GitHub Pages is free! (but has limitations - see below)

- GitHub Pages. There are a couple limitations of GitHub Pages including:

  - Space - Since I am using GitHub pages for my website, there are file size and repo size limits. Based on the data stored and as evidenced by various tests, txt files seem to use the least amount of space.

  - Static pages - GitHub only serves static files. This means I can't use PHP or something similar to connect to a database in the cloud to serve the information. It also means that the project pretty much has to be made using just HTML, CSS, and JavaScript.

- The Challenge. I saw this project as a challenge to fit everything within the constraints. This project has no cost or space overruns! It meets 100% of the specifications.
