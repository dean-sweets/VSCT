# Sherpa
Sherpa is a responsive, mobile first, front-end framework that helps front-end developers build modular, isolated, scallable sites.

### Features:
- **Less CSS pre-processor** - Use variables, imports and mixins in your CSS.
- **Browsersync live reload** - No more switching between windows and manually reloading.
- **Spins up a local server** - Run your typekit fonts, test in browserstack, etc.
- **Include files** - Easy as pie include files. Isolate your markup, build master pages, templates, etc.
- **Minify & Optimize** - Not only will Sherpa minify your code, but it will eliminate any unnecessary CSS when ready for production.

### Dependencies

Sherpa requires [Node](https://nodejs.org/) and [Grunt](http://gruntjs.com/getting-started)

1. First [download and install Node](https://nodejs.org/)

2. After installing Node, install Grunt globally
    - Install with `npm install -g grunt-cli`
    - If you need further instructions you can check out [Grunt's gettings started guide](http://gruntjs.com/getting-started)
3. *(Optional) Sherpa can also be downloaded through Bower. Run `npm install -g bower` to install Bower globally.*


### Getting Started

1. [Download zip](https://github.com/codesummit/Sherpa/archive/master.zip) or download through Bower `$ bower install sherpa`

2. CD to the root of your project folder and install node package dependencies. `npm install`

3. After that, run `grunt` and you'll be up and running! This will compile less, move all required assets to the `_output` folder and spin up a local server.

Next time you come into the project, just cd to the root and run `grunt` from the terminal

### Grunt Tasks
Run `grunt` (the default task) to initiate the following tasks:
 - **Less** - compiles `_input/less/main.less` to `_output/css/main.css`
 - **Watch** - watches files within the `_input` for changes
 - **Browser Sync** - Reloads browser on save, spins up a local server for all files in the `_output` folder. and mimics behavior across multiple browsers.
 - **Includes** - allows for include html files within the `_input` folder. Compiles to
 - **Copy** - copies the `img` folder within the `_input` folder to the corresponding folder in the `_output


 Other Grunt tasks
 - **CSS Minify** - `grunt cssmin` will minify the `_output/css/main.css` file
 - **Uncss** - `grunt uncss` will look at all html files in the `_output` folder and only include the css selectors within those documents in the `_output/css/main.css` filed
 - **`grunt minify`** - This custom task will run both above tasks together `cssmin` and `uncss`

### Contributing
We are still defining contributor guidelines. Feel free to contribute and make pull requests.

### License
Sherpa if free to use under the [MIT License](https://github.com/codesummit/Sherpa/blob/master/license.md) Copyright © 2015 [Codesummit](http://www.codesummit.com)

### Shoutouts
- Sherpa proudly uses [BrowseStack](http://browserstack.com) for cross-browser testing

![BrowserStack](http://www.xml2selenium.com/wp-content/uploads/2014/01/BrowserStackLogo.png)
- Our [contributors](https://github.com/codesummit/Sherpa/graphs/contributors)
