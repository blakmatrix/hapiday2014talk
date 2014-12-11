### How to View

Some reveal.js features, like external markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

3. Install dependencies
   ```sh
   $ npm install
   ```

4. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

5. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.




## License

MIT licensed

Copyright (C) 2014 Hakim El Hattab, http://hakim.se
