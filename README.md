# Swagger Starter Kit

This Swagger Starter Kit is a simple way to share a Swagger API specification file, and also make it interactive.


## Create a Swagger file

1. Create a Swagger file any way you like.

  * See the `examples` directory for simple examples.

  * You can name the file anything you want. A convention is to name the file `swagger.yaml` or `swagger.json`.

  * You can create the file by using any editor to write YAML or JSON, or you can create the file by using the [Swagger Code Generator](https://github.com/swagger-api/swagger-codegen/blob/master/README.md) or similar tool.

2. Put the file anywhere on the web.

  * We typically put the file at the top level of a site, such as `http://example.com/swagger.json`.

  * Browse to the URL. This verifies the file is readable by your web browser.

  * Browse to `http://petstore.swagger.io/` and enter the URL of the file. This verfies the file is readable by Swagger code.


## Create a Swagger server

1. Edit the files in this directory as you like.

   * Edit `index.html` to see how to add your file's URL as the default URL.

   * Customize anything you want, such as HTML, CSS, JS.

2. Copy everything in this directory to any directory on any webserver.

   * We typically put this at the top level of a site, such as `http://example.com/swagger/`.

   * This directory can be anywhere; it doesn't need to be in the same location as your `swagger.json` file.

   * Browse to the URL. This should load the Swagger code and also load your Swagger file.


## Swagger YAML to Swagger JSON

To translate Swagger YAML to Swagger JSON, you can do it any way you want.

  * If you want a quick web tool, then try [yamltojson.com](http://yamltojson.com/)

  * If you want a command line script, then try [yaml-to-json](https://github.com/SixArm/sixarm_unix_shell_scripts/blob/master/yaml-to-json)

  * If you want a powerful converter, then try [Swagger Code Generator](https://github.com/swagger-api/swagger-codegen/blob/master/README.md)


## How this repo relates to Swagger UI

This repository is based on the Swagger UI `dist` directory.

We make these adjustments:

  * Edit `index.html` to make it more user-friendly for novices, and independent of the Swagger "Pet Store" demo.

  * Remove unneeded directories and files, such as `fonts` and `typography.css`.

  * Move the swagger-*.js files to the `lib` directory.

Our goal is to have a simple way to serve a standalone Swagger file, without an extras such as fonts, images, code generation, etc.


## Work In Progress

Get feedback and suggestions from the Swagger community.

Continue cleaning out "Pet Store" items.


## To Do

Automate the tracking of Swagger UI: when Swagger UI `dist` is updated, we want this repo updated too.
