**Note**: This is a copy of [a fork](https://github.com/NotBobTheBuilder/grunt-inline-css) that uses an up to date version of Juice and has some bugfixes. We are copying it to our SpeakUp organization so as not to lose it should the original repo go down. --Alex Turpin

# grunt-inline-css

> Takes an html file with css link and turns inline. Great for emails. It leverages the amazing [juice](https://github.com/LearnBoost/juice) library.

## Getting Started
This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-inline-css --save-dev
```

One the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-inline-css');
```

## The "inlinecss" task

### Overview
In your project's Gruntfile, add a section named `inlinecss` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
	inlinecss: {
		main: {
			options: {
			},
			files: {
				'out.html': 'in.html'
			}
		}
	}
})
```

You can see available options [here](https://github.com/LearnBoost/juice#juicefilepath-options-callback)

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).
