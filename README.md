# AngularJS-boilerplate
A micro AngularJS boilerplate for start projects with mocking and routing modules ready,

based on this [Best Practice angular-styleguide made by johnpapa](https://github.com/johnpapa/angular-styleguide).

#### See this [Angular Scaffolding](https://github.com/damianopetrungaro/generator-angular-rest) for better and faster developing.

# Install

Make a directory and move into it

```sh
    $ mkdir myFolder
    $ cd myFolder
```

Then clone the boilerplate and install all dependecies

```sh
    $ git clone https://github.com/damianopetrungaro/AngularJS-boilerplate.git
    $ cd AngularJS-boilerplate
    $ npm install
```


## Set up environment

For developing env:

With watch and live reload for js and css (or sass)

```bash
	$  npm run serve
```

For production env:

Simply return minified code and optimizated images

```bash
	$  npm run prod
```



# Modules

The sample modules have a ``` .mock.js ``` and ``` .route.js ``` files.

Those files are used by the ``` core ``` for pass information to a provider.


If you want to remove a core module, just delete from the resources ( i.e ``` users ``` ) and the``` core ``` directory the file and folder.

Remember also to remove the modules injection to the ```app.module.js``` file
