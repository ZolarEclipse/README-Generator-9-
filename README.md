# readme_generator

![Unlicense](https://img.shields.io/badge/license-The_Unlicense-blue)

## Description

A README.md file generator built on node.js. This program will
generate a new README.md file in an output directory with values
that a user enters.

## Table of Contents

- [General Functionality](#general-functionality)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#licensing)
- [Contributing](#contributing)

### General Functionality

The program will ask a user questions that are needed to fulfill
the requirements of generating a unique and complete README.md file.

- Required Responses:

  A Github user name is required
  A `valid` email address is required

- License Selection:

  The [Github API](https://api.github.com/licenses) is used to populate the license options available.

### Installation

1.  Install Node.js version 20.x or newer
2.  Run `npm i` to load all the project dependencies
3.  Run the program via `node index.js`

### Usage

As mentioned in the installation instructions, you run the program with `node index.js`. This will launch an interactive question and answer session. Once the Q&A is complete a README.md file is created in the output directory.

You can watch a quick [video](https://youtu.be/beieGntMEx8) on how this works

There is a sample README.md located in [examples](./assets/examples/README.md)

### Credits

Thanks to Eric for helping me figure out to get the package to do it's job

### Licensing

Licensed with [The Unlicense](http://choosealicense.com/licenses/unlicense)
### Contributing

You can reach me at JAFadlovich@gmai.com