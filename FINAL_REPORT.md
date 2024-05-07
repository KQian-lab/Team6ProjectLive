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

[YouTube Video Link](https://youtu.be/80RhAbMyEc4)

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
- Flask: Flask is a lightweight Python web framework. It makes it easy to set up routing, which is the process of matching URLs to specific functions in the application. Used to create routes for pages.
- Render: Used to host static pages and game page
- SQLite: SQLite is a lightweight, file-based database that integrates well with Python, offering a user-friendly SQL interface ideal for quick development and small to medium applications. Used to update scores and manage leaderboards/personal bests

##### Game
- [Typescript](https://www.typescriptlang.org/): We went with Typescript over JavaScript due to its type safety and the ability to find errors before compiling. Although we ran into trouble with building the app, we likely would have encountered similar issues with JavaScript during the application build. Overall A great language to use. Used for the development of our game.
- [Phaser](https://phaser.io/): It is an HTML game engine that handles GUI and asset management. It also has an excellent arcade physics engine to build cool games using JavaScript or TypeScript as the programming language. Used to manage assets and physics for our game.
- [Vite](https://vitejs.dev/): Vite is a local development server written by Evan You, the creator of Vue.js. It uses Rollup and esbuild internally for bundling. It allows the user to have a fast-spinning local dev server and a setup that handles many of the modules needed, giving the user more time to focus on their project. Used to allow instantaneous refreshing and updating of our game locally to aid in development.
- [Rollup.js](https://rollupjs.org/): Rollup is a module bundler for JavaScript which compiles small pieces of code into something larger and more complex, such as a library or application. Utilized to build our game for hosting online. 
- [Neovim](https://neovim.io/): A great text editor made after Vim that allows Lua plugins to make it a full-fledged IDE.
- [GIMP](https://www.gimp.org/): GIMP is a free and open-source image manipulation tool made by the GNU project that allowed us to create digital assets for our game. 
- [Audacity](https://www.audacityteam.org/): Audacity is a free and open-source audio tool that allows us to make the game's sound effects and background music.

##### Project Management
- GitHub: [GitHub](https://github.com) is platform for developers to store and manage code in Git repositories. 
- Zoom: [Zoom](https://zoom.com) is a cloud based video conferencing platform used by the team for weekly meetings.  
- Discord: [Discord](https://discord.com) is a voice, video, and text communication platform with over 500 million users. Discord users can join or create communities, known as servers. For this project our team created a server for the group to communicate. 
- Monday.com: [Monday.com](https://monday.com) is a cloud-based collaboration, work-management, and CRM provider used by the team to manage the project. The platform's interface is easy-to-use and provides a dashboard view of each work item, it's owner, and status. There are pre-built templates such as Gantt charts and Kanban boards. A key selling point of the product is it's integration with other platforms including O365, Jira, Basecamp, and Slack. Competitors include Adobe Workfront, Asana, and Smartsheet.


#### 2. Testing
- Cross-Device Testing​
- Integration Testing​
- Functional Testing​: Game​
- Unit Testing: Database

#### 3. Implemented features
- Sign Up: When a user enters a three-character player name and a properly formatted email address, these are saved to the database, and a player ID is assigned. Upon successful signup, the user is redirected to the index page.
- Sign In: A user enters a playerName and email here. If that combination already exists in the database, the user successfully signs in and is redirected to the index page. If it does not exist in the database, the user cannot leave the sign-in page.
- My Best Score: Logged-in users can view their top 10 past game scores and the dates on which they were achieved.
- Leaderboard: Users can view the top 10 past game scores of all users, along with the player names who achieved them.
- Game explanation: Users can refer to the control guide and rules of the space game. They can learn how to shoot, how to dodge enemy attacks, and the details of special items and special events.
- Credits: The names of the creators of this game and the project production period are displayed.
- Space game: Here is the main part of the game. Below are the details.

#### 4. Detail of Space game (Game design)
- Shooting at enemies: Users earn 10 points for each enemy they defeat using the space key to control their spaceship.
- Dodging enemy attacks: Users can use the left and right arrow keys to dodge attacks from enemies and occasionally occurring meteors. Colliding with these will result in the loss of one health point.
- Collecting items: If the spaceship touches a repair part, it can recover one health point.
- Generating of the next set of enemies: Once a set of enemy fleets is completely defeated, the same set of enemy fleets will reappear, allowing the game to continue endlessly.

### What we were in the middle of implementing
- We do not have any ongoing implementations at the moment. Development has paused for now.

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

### Challenges

Initially, the project faced significant hurdles in building and deploying the web game. This challenge was crucial as it threatened the viability of delivering a functional game. The solution came through discovering and utilizing rollup.js, a module bundler for JavaScript that efficiently compiles small pieces of code into something larger and more complex, suitable for production environments. This tool was instrumental in overcoming the deployment issues.

Another significant challenge was managing the project's scope. We wanted to include numerous features and ideas, but practical constraints like time and resources often require a more focused approach. The team addressed this by evaluating the game's core objectives and gameplay mechanics, leading to a strategic decision to cut unnecessary features. This prioritization ensured that development efforts concentrated on enhancing the player's experience with the most impactful elements of the game.

Working remotely posed its own set of challenges for the web game project, particularly in terms of collaboration and communication among team members. GitHub allowed everyone to work on different parts of the game simultaneously without overwriting each other’s contributions. This not only streamlined the development process but also enhanced productivity by allowing asynchronous work. Scheduling and synchronizing meeting times also posed a challenge due to the varying availability of team members. The solution came in the form of When2meet, a scheduling tool that helped in finding suitable times for everyone to meet. We quickly decided on a common day and time to meet each week. Using discord for quick communication, we were able to reschedule or change our meetings as necessary.

## Public hosting site
[Team 6's Space game](https://team6projectlive.onrender.com/)

