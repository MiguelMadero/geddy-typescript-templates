geddy-typescript-templates
==========================

Contains typescript templates for geddy

__Disclaimer:__ This is __work in progress__ and __experimental__. The main purpose of this project at this stage is to test a new `template` switch in geddy's cli. The following is just the expected usage. geddy-*-templates aren't working in geddy, available on NPM, might not even contain real templates and typescript or other template features might not be supported by geddy.


## Using from NPM

npm install it in your geddy app

`$ npm install geddy-typescript-templates`

Scaffold your app using the new templates

`$ npm scaffold todo title:default status --template typescript`

Voila. Scaffold will use the files from this module instead of the default templates. 

## Installing globally

npm install it globally

`$ npm install geddy-typescript-templates -g`

Now you can create a new app using the base scripts on this module

`$ geddy app myapp --template typescript`

Voila. v.s.

## Cloning from GitHub

Clone this repo

`$ git clone https://github.com/MiguelMadero/geddy-typescript-templates.git`

Create a base app or scaffold using the --template switch

`geddy app myapp --template /path/to/the/cloned/repo

Voila. Ditto