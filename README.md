### Deux Codes

A CodePen-like clone that I used to run. It helped people within my developer community connect by __pair programming__.

<br>

Tagline: _Real time pair coding in a HTML/CSS/JS playground. Powered by socket.io and Node.js._

![alt text](https://raw.githubusercontent.com/healeycodes/deux-codes/master/public/img/js.png "Image of a room on Deux Codes")

Any code you enter will be streamed with your private room, character by character. As a user's code area is changed, their preivew iframe will follow, keeping everyone in sync. You can fork or delete rooms, and import any external scripts you need via `<script>` tags. Rooms are automatically saved every half-second.

<br>

### Tech Stack

Back end: Node.js, Express with EJS templates, socket.io, PostgreSQL via Sequelize.

Front end: HTML5/CSS3, JQuery, Bootstrap, srcdoc-polyfill.

Tested with: Jest, SuperTest.

<br>

### Build

1. `npm install`

<br>

### Tests

1. Edit `"test"` in `config/config.json` with your PostgreSQL server details.

2. Run `npm test`

<br>

### Run

1. Edit `"production"` in `config/config.json` with your PostgreSQL server details.

2. Run `node app.js`
