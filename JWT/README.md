# JSON Web Token (JWT)

JWT is an internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims.

JWT tokens are signed either using a private secret or a public/private key.

The tokens are designed to be compact, URL-safe and usable in a web-browser single-sign-on context.

## Pros

- No databse table, this means fewer database queries so faster response times.
- Simpler to use, if careful.

## Cons

- Reliance on single secret key.
- Client can't be mananged from the server.
- Data overhead.
- Complicated to understand.

![](https://cdn2.auth0.com/docs/media/articles/api-auth/client-credentials-grant.png)
