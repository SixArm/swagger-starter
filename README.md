# Swagger Starter Kit

Swagger Starter Kit is a simple way to share a Swagger API specification file.

This project is based on the [Swagger UI](https://github.com/swagger-api/swagger-ui) project.

To get started, look in the `examples` directory and see the `swagger.yaml` file.

For more about Swagger, see the (Swagger API)[https://github.com/swagger-api] page.

## Create a Swagger file

Create a Swagger file any way you like:

  * You can name the file anything you want. Convention is `swagger.yaml` or `swagger.json`.

  * You can create the file by using any editor to write YAML or JSON.

  * If you want more power, try the [Swagger Code Generator](https://github.com/swagger-api/swagger-codegen/blob/master/README.md).

If your file uses YAML, then translate it to JSON:

  * For a quick web tool, try [yamltojson.com](http://yamltojson.com/)

  * For a command line script, try [yaml-to-json](https://github.com/SixArm/sixarm_unix_shell_scripts/blob/master/yaml-to-json)

  * For a powerful converter, try [Swagger Code Generator](https://github.com/swagger-api/swagger-codegen/blob/master/README.md)

Host the file anywhere on the web:

  * We typically put the file at the top of a site, such as `http://example.com/swagger.json`.

  * Browse to the URL. This verifies the file is readable by your web browser.

  * Browse to `http://petstore.swagger.io/` and enter the file's URL. This validates the file.


## Create a Swagger server

Edit the files in this directory as you like:

   * Edit `index.html` to see how to add your file's URL as the default URL.

   * Customize `index.html` if your API uses an API key, or authentication token, etc.

   * Customize anything else you want, such as HTML, CSS, JS.

Copy everything here to any directory on any webserver:

   * We typically put this at the top level of a site, such as `http://example.com/swagger/`.

   * This directory can be anywhere; it doesn't need to be with your `swagger.json` file.

   * Browse to the URL. This loads the Swagger code and your Swagger file.


## How this repo relates to Swagger UI

This repository is based on the Swagger UI `dist` directory.

We make these adjustments:

  * Edit `index.html` to make it easier for novices, and to remove the "Pet Store" demo.

  * Delete unneeded directories and files, such as `fonts` and `typography.css`.

  * Move the swagger-*.js files to the `lib` directory.


## Work In Progress

Get feedback and suggestions from the Swagger community.

Continue cleaning out "Pet Store" items.


## To Do

Automate the tracking of Swagger UI:

  * When Swagger UI `dist` is updated, we want this repo updated too.

Consider suggesting this starter kit as a top level Swagger project.

  * If people are interested in this, please let us know, and we'll proceed.
