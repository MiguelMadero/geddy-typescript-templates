geddy-typescript-templates
==========================

Contains typescript templates for geddy


__NOTE:__ typescript isn't currently supported in geddy. If you want to try another template have a look at [geddy-coffee-templates](https://github.com/MiguelMadero/geddy-coffee-templates).


__Disclaimer:__ This is __work in progress__ and __experimental__. The main purpose of this project at this stage is to test a new `template` switch in geddy's cli. 


## Using from NPM

npm install it in your geddy app

`$ npm install geddy-typescript-templates`

Scaffold your app using the new templates

`$ npm scaffold todo title:default status --templates typescript`

Voila. Scaffold will use the files from this module instead of the default templates. 

## Installing globally

npm install it globally

`$ npm install geddy-typescript-templates -g`

Now you can create a new app using the base scripts on this module

`$ geddy app myapp --templates typescript`

Voila. v.s.

## Cloning from GitHub

Clone this repo

`$ git clone https://github.com/MiguelMadero/geddy-typescript-templates.git`

Create a base app or scaffold using the --templates switch

`geddy app myapp --templates /path/to/the/cloned/repo`

Voila. Ditto