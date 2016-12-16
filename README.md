# ContentEditor

> A JS library for building WYSIWYG editors for HTML content. Stolen from https://github.com/GetmeUK/ContentTools with few useful additions

<a href="http://getcontenttools.com"><img width="728" src="http://getcontenttools.com/images/github-splash.png" alt="Demo"></a>

## Install

**Using bower**

```
bower install --save ContentTools
```

**Using npm**

```
npm install --save ContentTools
```

## Building
To build the library you'll need to use Grunt. First install the required node modules ([grunt-cli](http://gruntjs.com/getting-started) must be installed):
```
git clone https://github.com/GetmeUK/ContentTools.git
cd ContentTools
npm install
```

Install Sass (if not already installed):
```
gem install sass
```

Then run `grunt build` to build the project.

## Testing
To test the library you'll need to use Jasmine. First install Jasmine:
```
git clone https://github.com/pivotal/jasmine.git
mkdir ContentTools/jasmine
mv jasmine/dist/jasmine-standalone-2.0.3.zip ContentTools/jasmine
cd ContentTools/jasmine
unzip jasmine-standalone-2.0.3.zip
```

Then open `ContentTools/SpecRunner.html` in a browser to run the tests.

Alternatively you can use `grunt jasmine` to run the tests from the command line.

## ContentTools via jsdelivr

ContentTools is available via the [jsdelivr open source CDN](http://www.jsdelivr.com/), to reference a file from the ContentTools build directory use the following URL format:

`http://cdn.jsdelivr.net/contenttools/{verision}/{file}`

For example to access the current primary JavaScript file the URL would be:

`http://cdn.jsdelivr.net/contenttools/1.3.1/content-tools.min.js`

As the project's CSS uses relative file paths you will need to either role your own version of CSS from the SASS files (recommended) or [override references to fonts/images within your local CSS](https://gist.github.com/anthonyjb/a6aec8ecfbfe6f875d5c6691687ba43d).


## Documentation
Full documentation is available at http://getcontenttools.com/api/content-tools

