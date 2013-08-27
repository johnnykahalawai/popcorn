Popcorn
===============

![Screenshot](assets/image/screenshot.jpg)

[Live Demo](http://montagejs.org/apps/popcorn/)

This demo application showcases how to structure and optimize a MontageJS application for tablets.

##Installation

To run the Popcorn demo locally, you must have Node.js and npm installed. MontageJS application development depends on npm, the Node package manager, which is distributed with Node.js. If you haven't done so already, be sure to [download](http://nodejs.org/download/) and run the prebuilt Node.js installer for your platform from the Node.js website. Then follow these steps:

1. Clone the popcorn [GitHub repo](https://github.com/montagejs/popcorn) in your desktop.

2. Use your command line tool to navigate to the cloned directory and install the modules required to run the demo:
        
   ```
   cd popcorn
   npm update
   ```
    
3. Spin up your preferred HTTP server and point your browser to the associated port.

    > During development MontageJS applications rely on XHR to load their various components and modules, which is why you will need a web server to serve the demo.

    > If you happen to have [minit](https://github.com/montagejs/minit), the Montage Initializer, installed (`npm install minit -g`) you can run `minit serve` from within the demo directory to set up a server on demand.


## Application Structure

Folder / File | Description |
------------ | ------------- 
assets | Contains global styles and images for the application.
model | Contains the data model.
index.html | Is the entry-point HTML document.
LICENSE.md | Contains copyright information.
package.json | Describes your app and its dependencies.
README.md | Provides information about the demo application and how to install it.
ui | Contains the user interface components of the demo application.

## Contact Us

Got questions? Join us on [irc.freenode.net#montage](http://webchat.freenode.net/?channels=montage).

Got feedback or want to report a bug? Let us know by creating a new [GitHub issue](https://github.com/montagejs/popcorn).

## Credit

This demo application was created by [MontageJS](http://montagejs.org).

