## Project Title
Team 6's Space game

## Team members
- Seiji Aoyama
- Stephen Donlin
- Kevin Qian
- Patrick Sharp

## Project tracker link
[Monday.com](https://colorado-cspb.monday.com/boards/6042697831)

## Link to 5 minute video: a demo for a potential customer


## Version control repository link
[Github](https://github.com/KQian-lab/Team6ProjectLive)

## Final Status Report and reflection

### What we completed
- Leaderboard Page
- Game Explanation Page
- Homepage
- My Personal Best Page
- SQL functions for updating leaderboard
- SQL functions for updating my personal best
- Signin/Credits Page
- Sign up functionality
- Flask App and routes
- Successfully hosted Game and static pages
- Created functioning game
  - Score tracking and updating
  - Obstacles
  - Enemies
  - Powerups
  - Bullets
  - RNG Entity Spawning
#### 1. Selection of the Technology Stack and Reasons

##### Design
- Figma: Figma is a web-based UI design tool that allows for quick creation of rough designs and interactive prototypes. It supports real-time collaboration, making it ideal for remote teams.

##### Frontend
- Javascript
- HTML / CSS

##### Backend
- Python: Coding language utilized in tthis project for the purpose of creating API routes and working with sqlite
- Flask: Flask is a lightweight Python web framework. It makes it easy to set up routing, which is the process of matching URLs to specific functions in the application.
- Render
- SQLite: SQLite is a lightweight, file-based database that integrates well with Python, offering a user-friendly SQL interface ideal for quick development and small to medium applications.

##### Game
- [Typescript](https://www.typescriptlang.org/): We went with Typescript over JavaScript due to its type safety and the ability to find errors before compiling. Although we ran into trouble with building the app, we likely would have encountered similar issues with JavaScript during the application build. Overall A great language to use.
- [Phaser](https://phaser.io/): It is an HTML game engine that handles GUI and asset management. It also has an excellent arcade physics engine to build cool games using JavaScript or TypeScript as the programming language.
- [Vite](https://vitejs.dev/): Vite is a local development server written by Evan You, the creator of Vue.js. It uses Rollup and esbuild internally for bundling. It allows the user to have a fast-spinning local dev server and a setup that handles many of the modules needed, giving the user more time to focus on their project.
- [Rollup.js](https://rollupjs.org/): Rollup is a module bundler for JavaScript which compiles small pieces of code into something larger and more complex, such as a library or application.
- [Neovim](https://neovim.io/): A great text editor made after Vim that allows Lua plugins to make it a full-fledged IDE.
- [GIMP](https://www.gimp.org/): GIMP is a free and open-source image manipulation tool made by the GNU project that allowed us to create digital assets for our game. 
- [Audacity](https://www.audacityteam.org/): Audacity is a free and open-source audio tool that allows us to make the game's sound effects and background music.

##### Project Management
- Discord
- Zoom
- GitHub
- Monday.com 

[Monday.com](https://monday.com) is a cloud-based collaboration, work-management, and CRM provider used by the team to manage the project. The platform's interface is easy-to-use and provides a dashboard view of each work item, it's owner, and status. There are pre-built templates such as Gantt charts and Kanban boards. A key selling point of the product is it's integration with other platforms including O365, Jira, Basecamp, and Slack. Competitors include Adobe Workfront, Asana, and Smartsheet.


#### 2. Testing
- Cross-Device Testing​
- Integration Testing​
- Functional Testing​: Game​
- Unit Testing: Database

#### 3. Implemented features
- Sign Up: When a user enters a three-character player name and a properly formatted email address, these are saved to the database, and a player ID is assigned. Upon successful signup, the user is redirected to the index page.
- Sign In
- My Best Score
- Leaderboard
- Game explanation
- Credits
- Space game

#### 4. Detail of Space game (Game design)



### What we were in the middle of implementing

### What we had planned for the future
- Improve User interface.
- Increase the difficulty of the game based on the score obtained or the elapsed time. Currently, the difficulty level is constant.
- Implement sign-out functionality.
- Maintain sign-in status with cookies.
- Add multiple spaceships, obstacles, and items.
- Adjust screen scaling to fit browser size

### Any known problems (bugs, issues)
- Not immediately game over even if hit by a meteor.
- Redirect to an error page that should not be shown to users, intended for developers only, when an exception is detected in user input during signup

### Reflection
- "Challenge"
- ""

## Public hosting site
[Team 6's Space game](https://team6projectlive.onrender.com/)

