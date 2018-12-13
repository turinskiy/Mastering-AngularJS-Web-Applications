# Mastering-AngularJS-Web-Applications
## Page 80th

### Serverside:
_______________
+ Express (http://expressjs.com/) as the server-side web application 
framework that can provide routing, serve data and static resources.
+ Passport (http://passportjs.org/) as a security middleware for node.js.
+ Restler (https://github.com/danwrong/restler) as an HTTP client library 
for node.js.

### Build system:
_______________
+ JavaScript source code must be checked for compliance with coding 
standards using tools like jslint (http://www.jslint.com/), jshint  
(http://www.jshint.com/) or similar.
+ Test suites should be executed as often as possible; at least as part of  
each and every build. As such testing tools and processes must be  
tightly integrated with the build system.
+ Some bles might need to be generated (for example CSS bles from  
templates like LESS).
+ Files need to be merged together and minibed to optimize  
in-browser performance.

### Tools:
Grunt, Jasmine + Karma
_______________

### Folder structure
1. `src` It contains application's source code
    1. `app`
    2. `assets`
    3. `common`
    4. `less`
    5. _index.html_
2. `test` It contains accompanying automated tests
3. `vendor` It contains third party dependencies
4. `build` It contains build scripts
5. `dist` It contains build results, ready to be deployed in a target environment
