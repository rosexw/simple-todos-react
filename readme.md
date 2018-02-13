https://www.meteor.com/tutorials/react/creating-an-app

To create the app, open your terminal and type:

meteor create simple-todos
This will create a new folder called simple-todos with all of the files that a Meteor app needs:

client/main.js        # a JavaScript entry point loaded on the client
client/main.html      # an HTML file that defines view templates
client/main.css       # a CSS file to define your app's styles
server/main.js        # a JavaScript entry point loaded on the server
package.json          # a control file for installing NPM packages
package-lock.json     # Describes the NPM dependency tree
.meteor               # internal Meteor files
.gitignore            # a control file for git
To run the newly created app:

cd simple-todos
meteor

To open the app, simply open your web browser and go to http://localhost:3000 to see the app running.

There are NPM packages required to run the code:
meteor npm install --save react react-dom
