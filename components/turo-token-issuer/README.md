# How to use this

Add the following to your `deployment.toml` file:

```toml
[oauth.extensions.token_types.token_type]
name = "JWT"
issuer = "com.turo.is.tokenIssure.ExtendedJWTTokenIssuer"
```