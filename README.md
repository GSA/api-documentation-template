***2019 Update: Instead of using this template, GSA teams can host their API documention directly on the GSA API directory. Instructions are available here: https://github.com/GSA/open-gsa-redesign/blob/master/APIDOCS.md***


API Documentation Template
====================


This a documentation template for GSA APIs provided by GSA Digital Services to provide a consistent look and feel for GSA APIs.  

Thanks to CFPB team for creating this model and for furthering open source in government.  Additional thanks to the 18F and SAM (IAE) teams as well as several in the private sector.

## Using This Template In GitHub Pages
Currently this template is configured to work on GitHub pages. The easiest way to use this template is by cloning this repo and using it as a starting point for your own project. 

The source URL for this repository (used in both methods below) is: https://github.com/GSA/api-documentation-template.git

### Cloning this repository from the Command Line
* If you have enabled two-factor authentication (GSA requirement) you will need to [create an access token for the command line](https://help.github.com/articles/creating-an-access-token-for-command-line-use/). (Save the token and use in next step.)
* Then follow instructions for [duplicating the repository](https://help.github.com/articles/duplicating-a-repository/). Use the token you generated in place of the password.

### Cloning this repository from the Github web interface
* From your github home page, select "[start a project](https://github.com/new)" or "[new repository](https://github.com/new)".
* Create this repository in the GSA organization.
* Enter the appropriate information for the new repository you are creating. Do not select "initialize this repository with readme".
* On the next page, select "import code from another repository".
* The next page is titled "Import Your Project To Github". In the box below "Your old repository’s clone URL", enter the source URL for this repository (listed above). Click "begin import".
* When the import is completed, you should see the "import complete" message.

We recommend that your API documentation reside in a dedicated repository -- separate from your API code. However, these pages reside in the "docs" so that they can also be included inside a repo with API code. Either way, you will need to update the Settings/Github Pages "source" to use "master/docs". 

### Making the cloned repository your own
* Modify the readme.md in the master branch with the name and details of your own documentation.
* In the repository settings, make this repository public. (Keep in mind you won't be able to put sensitive information in it.)
* Enable the GitHub pages web site by going to "Settings". In the "GitHub Pages" section, select "Master Branch /docs folder" and click the save button.
* GitHub will display a URL to your documentation web site. You will need to add "api-docs/" to this path to access the web site.
* You can add the link to this web page on the "code" tab of your repository (see this repo for an example). Go to the "code" tab of your repository, and click the "edit" button toward the top of the page. Enter the URL to your documentation (remember to add "api-docs/") in the "website" box, and add your own description in the "Description" box. Click save. You should see the link at the top of the "code" tab.

### Running the Repository Locally (may need to update this to use bundler)
* This repository requires a local Jekyll environment to run locally. Full instructions are available on the Jekyll website [here](https://jekyllrb.com/docs/installation/)
* Once installed, navigate to the `/docs` folder in the terminal and enter `bundle exec jekyll serve`

## Note About The API Calls
The "API Calls" tab of this documentation is a demonstration of the Swagger UI to provide interactive sample calls to the API. Most of this resides in the "console" sub-folder.

This is using the [Open API Specification](http://swagger.io/specification/). Other options provide similar modeling and tooling, including [RAML](http://raml.org/), [API Blueprint](https://apiblueprint.org/), and several more.

## Helping us improve
Please feel free to add issues and pull requests for any recommendations you think would be worthwhile for all users of the template.
