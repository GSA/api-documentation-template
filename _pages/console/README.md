Using API Calls Page (/console)
====================

This readme explains some of the intricacies of using the API Calls page, which is in the /console directory of this project. (Some of these intricacies could be improved by future updates.)

## Navigation Bar
The API Calls page has a hard-coded version of the navigation bar that matches the rest of the site.

You can find it in the /console/index.html file by searching for class="page-title". Notice that the relative path of the links are different in this page than in the master nave bar (which is in the _includes).


## Swagger Container
The Swagger UI container is injected into the DOM by JavaScript. If you are looking at the output HTML, you will see that it begins with this tag: 

```
<div id="swagger-ui-container" class="swagger-ui-wrap"> 
```

The actual contents of the Swagger UI Container are generated on the fly from the source OAS specification file: /console/citypairs.json 

This file can be edited with the online tool: [editor.swagger.io](http://editor.swagger.io/).
