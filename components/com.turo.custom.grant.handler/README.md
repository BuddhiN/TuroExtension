# How to use this

Add the following to your `deployment.toml` file:

```toml
[oauth.grant_type.refresh_token]
grant_handler = "com.turo.custom.grant.handler.JwtRefreshGrantHandler"
```