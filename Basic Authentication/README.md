# Basic Authenticaiton

Basic Authentication is a method for a HTTP user agent (e.g. a web browser) to provide a user and password when making a request.

When using basic HTTP authentication, a request contains a header field in the form of `Authorization: Basic <credentials>`, where credentials is Base64 encoding of ID and password joined by a singel colon `:`
