# Introduction

Welcome to the MailUp Rest API reference! You can use our API to access Kittn API endpoints, which can get information on various cats, kittens, and breeds in our database.

We have language bindings in Http, Shell, C#, Javascript and Go! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

This example API documentation page was created with [Slate](https://github.com/tripit/slate). Feel free to edit it and use it as a base for your own API's documentation.

## Getting started

+ Read our [best practices](#best_practices) to understand what you can do and learn the recommended approaches.
+ <a href="http://help.mailup.com/display/mailupapi/Ready+to+go+in+15+minutes" target="_blank">**Download Demo Client**</a> and choose among several available programming languages.
+ Test Resource Access with your MailUp account. Don't have one? Request a <a href="http://help.mailup.com/display/mailupapi/Get+a+Developer+Account" target="_blank">developer account</a>.
+ After getting acquainted with the API, <a href="http://help.mailup.com/display/mailupapi/Authenticating+with+OAuth+v2" target="_blank">get your API keys</a> & build your own application.

## Integrating your application

A few things to keep in mind:
+ The MailUp REST API uses **Oauth2** and requires a token refresh. You can use the available samples to see how to refresh the authorization token
+ By properly setting the request header you can set the response format as JSON or XML
+ Each application is tied to a set of application keys, which are used to authorize the application (get yours).
+ Users of the application will be authenticated using their own MailUp account credentials.
+ The application keys used in the sample code shall not be used in a production environment.