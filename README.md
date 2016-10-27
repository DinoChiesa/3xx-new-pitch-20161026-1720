# New Pitch

### Full setup

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

1. Clone the reveal.js repository
   ```sh
   $ git clone https://github.com/DinoChiesa/3xx-new-pitch-20161026-1720 new-pitch
   ```

1. Navigate to the reveal.js folder
   ```sh
   $ cd new-pitch
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view the presentation

   You can change the port by using `npm start -- --port 8001`.


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)


## License

MIT licensed

Reveal is Copyright (C) 2016 Hakim El Hattab, http://hakim.se
Pitch is Copyright (C) 2016 Apigee Corp. 
