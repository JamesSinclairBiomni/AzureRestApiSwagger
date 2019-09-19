# AzureRestApiSwagger

Microsoft have supplied swagger.json files for all of their [Azure rest api's](https://github.com/Azure/azure-rest-api-specs).

This repo allows you to stand up a swagger UI website that will reference those api's, that said it'll allow you to point at any publically available swagger.json / OpenApi spec.

Simply edit the data.json file to add/remove entries from the site and copy the lot on to a webserver.

NB: the webserver that you run this on will possibly need a mime type adding for json files (.json, text/plain)
