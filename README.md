#BEM
A talk on the BEM naming convention.

##[GitHub Pages Link](https://chriskonings.github.io/bem/)

##This presentation was made with [Reveal.js](http://lab.hakim.se/reveal-js/)

###Full setup

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the fed-speaking--bem repository
   ```sh
   $ git clone git@github.ibm.com:CIngham/fed-speaking--bem.git
   ```

5. Navigate to the presentation folder
   ```sh
   $ cd fed-speaking--bem
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation
