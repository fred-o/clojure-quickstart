# Clojure Quickstart Archetype

This maven archetype will get you up, running, building, and distributing a clojure command line application lickity-split.

## Features

- bundled configuration for appassembler: `mvn package` will create a archive suitable for distribution, including a launcher script and bundled dependencies
- AOT compilation support using the snazzy clojure compiler maven plugin


## Installation

The simplest way to leverage this archetype is to install it into your local maven repo like so:
  
    git clone git://github.com/nullstyle/clojure-quickstart.git
    cd clojure-quickstart
    mvn install

## Usage

Install the plugin (see above), then use:

  	mvn archetype:generate

A long list of archetypes will be presented; pick clojure-quickstart (local archetypes are listed first so look near the top of the list).  Fill in the groupID and artifactID when prompted, choose a version or use the default, and then you're good to go.

## License

This project is licensed under the MIT license.

## TODO
- Add testing support
- Add repl support

## Contributing

Email patches to nullstyle@gmail.com, or send a pull request on Github.