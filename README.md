API Documentation Template
====================

This a documentation template for GSA APIs provided by GSA Digital Services to provide a consistent look and feel for GSA APIs.  

Thanks to CFPB team for creating this model and for furthering open source in government.  Additional inspiration from the 18F and the SAM (IAE) teams, as well as several in the private sector.

## Using This Template In GitHub Pages
Currently this template is configured to work on GitHub pages. The easiest way to use this template is by cloning this repo and using it as a starting point for your own project. 

The source URL for this repository (used in both methods below) is: https://github.com/GSA/api-documentation-template.git

### Cloning this repository from the Command Line
* If you have enabled two-factor authentication (GSA requirement) you will need to [create an access token for the command line](https://help.github.com/articles/creating-an-access-token-for-command-line-use/). (Save the token and use in next step.)
* Then follow instructions for [duplicating the repository](https://help.github.com/articles/duplicating-a-repository/). Use the token you generated in place of the password.

### Cloning this repository from the Github web interface
* From your github home page, select "[start a project](https://github.com/new)" or "[new repository](https://github.com/new)".
* Enter the appropriate information for the new repository you are creating. Do not select "initialize this repository with readme".
* On the next page, select "import code from another repository".
* The next page is titled "Import Your Project To Github". In the box below "Your old repository’s clone URL", enter the source URL for this repository (listed above). Click "begin import".
* When the import is completed, you should see the "import complete" message.

We recommend that your API documentation reside in a dedicated repository -- separate from your API code. However, these pages reside in the "docs" so that they can also be included inside a repo with API code. Either way, you will need to update the Settings/Github Pages "source" to use "master/docs". 

It is also helpful to put a link on the "Code" tab of your GitHub repo to the working docs page (see above for example). Notice that you should add "/api-docs/" to the location that GitHub generates, to find the home page of your doco.

## Note About The API Calls
The "API Calls" tab of this documentation is a demonstration of the Swagger UI to provide interactive sample calls to the API. Most of this resides in the "console" sub-folder.

This is using the [Open API Specification](http://swagger.io/specification/). Other options provide similar modeling and tooling, including [RAML](http://raml.org/), [API Blueprint](https://apiblueprint.org/), and several more.

## Helping us improve
Please feel free to add issues and pull requests for any recommendations you think would be worthwhile for all users of the template.
