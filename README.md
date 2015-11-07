sails-apidocs
=============

Automatically generate documentation for a Sails.js API from Sails blueprints and inline code documentation

### Manual Install

~~~bash
npm install sails-apidocs
~~~

### Automatic Install

Edit file **package.json**:
~~~json
"dependencies": {
...
	"sails-apidocs": ">= 0.0.3"
...
}
~~~
Then run:
~~~bash
npm install
~~~

### Usage
From project root run:
~~~bash
node node_modules/sails-apidocs/gendocs.js
~~~

### Output
Open **assets/docs/index.html** in browser

