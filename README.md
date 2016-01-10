<h1> React Starter Project w/ Webpack </h1>
<p>I made this to get up and running with React and Webpack quickly.</p>

<h2> To Use: </h2>
<ol>
  <li>Clone this repo onto your machine.</li>
  <li>Go into the project directory and run:  npm install.</li>
  <li>Run the command:  npm run dev</li>
  <li>In a different terminal window go into the src/client directory in the project.</li>
  <li>In src/client (where index.html exists) start a web server:  python -m SimpleHTTPServer</li>
  <li>Open up your browser to localhost:8000 or whatever port you specified for the web server.</li>
</ol>

<h2> Notes on usage </h2>
<p>
  In the webpack.config.js file we have specified that webpack should bundle all of the JavaScript together in the src/client/public/bundle.js file, including using babel to transpile ES6 to ES5.
</p>
<p>
  The 'npm run dev' script runs 'webpack -d --watch' so webpack watches for changes to the project. When changes are made you just need to refresh the webpage to see the changes.
</p>
<p>
  The other npm script, 'npm run build', uses 'webpack -p' to build a production-ready file in the bundle.js file.
</p>
