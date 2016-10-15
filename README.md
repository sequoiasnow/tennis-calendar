# Tennis Folder Upcoming Calendar.

The upcoming calendar displays events in a certain format using
some clever css and javascript.

To include Calendar on your project, clone this repository and run

```
npm install
npm build:js
npm build:css
```

This should create a css and js file both of which should be included
on your site. You must also include `jQuery` and `font awesome`.

To create a new calendar object in a sample element, such as
`<div id="soon-to-be-callendar"></div>`. Create a new calendar object
with that div attatched.

```js
new Calendar('#soon-to-becallendar', [...myListOfEvents]);
```

To see an example open index.html.


The compiled files are already included in this repo in the dist
directory.
