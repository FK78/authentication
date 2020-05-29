# Basic Authentication

Basic Authentication is a method for a HTTP user agent (e.g. a web browser) to provide a user and password when making a request.

When using basic HTTP authentication, a request contains a header field in the form of `Authorization: Basic <credentials>`, where credentials is Base64 encoding of ID and password joined by a singel colon `:`.

## Pros

- The implementation is simple as there is no encryption invovled.
- Less time to respond as it has only one call.
- Less code due to the lack of token creation and encryption method.
- Information is retrieved from the server with just one call therefore making it faster than other complex authentications.

## Cons
- SSL takes time to run basic HTTP so this will make the response time slow.
- Lack of SSL means users can be exposed to MITM.


![image](https://media.prod.mdn.mozit.cloud/attachments/2017/02/21/14689/3a44ec0bfe7597613dfb913e450a68eb/HTTPAuth.png)
