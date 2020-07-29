# client

Sign up at [News API](https://newsapi.org/), copy your API key.
Create a .env file in the root directory and past your API key as NA_KEY=<YOUR_API_KEY>

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)
* [Firebase](https://firebase.google.com/)

## Installation

* `git clone <repository-url>` this repository
* `cd client`
* `npm install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

* `$ npm install -g firebase-tools`
* `$ ember build --prod`
* `$ firebase login`
* `$ firebase init`

### Questions and answers:

What Firebase CLI features do you want to setup for this folder? ==> Hosting

What Firebase project do you want to associate as default? ==> Select your project.

What file should be used for Database Rules? ==> Just accept the database.rules.json with hitting Return/Enter.

What do you want to use as your public directory? ==> Type: dist, because we would like to publish the content from our dist folder.

Configure as a single-page app (rewrite all urls to /index.html)? ==> Answer: YES (Please note, the default answer would be N, so you have to type YES.)

File dist/index.html already exists. Overwrite? ==> NO!!! Accept the default NO.

* `$ firebase deploy`


## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

