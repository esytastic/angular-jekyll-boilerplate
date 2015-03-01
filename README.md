## angular-jekyll-integration

Angular Blog boilerplate using Gulp, Bower, Browserify and Jekyll.

## Integration
The integration between Angular and Jekyll was done by initializing the angular root scope with an array of post objects through ngInit directive.

The downside of this approach is that if a change to the index.html itself needs to be done, the index.html file that should be changed is the one inside the jekyll folder, which might seem to feel unnatural if you have ever worked with an AngularJS project.

## References

To create this boilerplate I used another boilerplate project as a reference, which can be accessed through this [link](https://github.com/MatayoshiMakoto/angular-gulp-bower-browserify-boilerplate).


## Quick Start

1. Make sure you have node.js installed;
1. Clone the repo;
1. Install the global requirements: `npm install -g gulp bower browserify`;
1. Install the local requirements: `npm install`;
1. Install the Bower components: `bower install`;
1. Install the Jekyll: `sudo gem install jekyll`;
1. Install the markdown language: `sudo gem install rdiscount`
1. Run locally with `gulp` and access it through  `http://localhost:5000/`;
1. Create a build: `gulp build` and preview it through `http://localhost:9999/`.

## Clean

If you want to clean both dist and dev folders you can run: `gulp clean`

## Posts

Any new post should be created inside the jekyll directory under post/_posts using Jekyll/Liquid convetions. For more info