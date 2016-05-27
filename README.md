# react-yelp-clone
Yelp clone using React and Google Maps, sample project from React book

My plan is to use this as a basic framework to explore some other aspects of a geographic store directory with multiple APIs.

The basis of the project is from the React book by Fullstack.io.

***


### Notes:

(Where I list errata & make suggestions)

Proceeding from the original docs (if you are not cloning this, but instead following the tutorial instructions):

-   The first time starting the webpack server: In Windows dev environment you have to put the command "node_modules/.bin/hjs-dev-server" into the package.json file

    So like:

        "scripts": {
    	    "test": "echo \"Error: no test specified\" && exit 1",
    	    "start":"./node_modules/.bin/hjs-dev-server"
          },

    Then you run this script with the command:

    npm start

    That gets you going.


***

The MIT License (MIT)

Copyright (c) 2015 Fullstack.io <fullstack.io>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
