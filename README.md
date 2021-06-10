# Typescript Library Template
Use the button on the top right (Use this template) to make your own package with this template.

## Customize the package.json
Change the values in the package.json. Especially those with values enclose in <>, namely:

- name
- description
- keywords
- author
- license

For more info on the config values see https://docs.npmjs.com/cli/v6/configuring-npm/package-json

## Add a LICENSE file
Add a file called LICENSE to the project root (same folder as the package.json).
A license is optional, but they make it possible to share your library more easily under legal aspects.

Read more on the issues of not licensing your software here: https://choosealicense.com/no-permission/

The same site can give you an overview of different licenses as well: https://choosealicense.com/

To add your LICENSE file more easily click in Github in your repository "Add file". Set the file name as LICENSE you
should then see a button to the right saying "Choose a license template".

## Install dependencies
As usual with `npm install` in the project root.

## Create your library
Start hacking away at your library. A few template examples are presented to give an idea how you can do it. Feel free 
to deviate though.

You can run tests and get coverage with `npm test`. You can reformat your code with `npm run format`. For a better 
developer experience you may want to look into IDE support for prettier and jest.

Feel free to change any settings (i.e. test settings) to fit your needs and taste.

## Publish you library
The current version is set to 0.0.0 on purpose, in order to get an appropriate version number with the `npm version` 
command right away. You can publish a major, minor and patch version as follows:

`npm version major` -> 1.0.0 on first run

`npm version minor` -> 0.1.0 on first run

`npm version patch` -> 0.0.1 on first run


## Change the README
This README will not fit your project. Describe your project here instead.

## Question and Improvements
If you have any improvements or question please leave them as an issue in this repository
