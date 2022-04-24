# oidc-siwe-app

Submission for https://amsterdam.ethglobal.com/

A graphical attempt at understanding a bit more the process when using [OpenID Connect](https://openid.net/specs/openid-connect-core-1_0.html) and [Sign-in with ethereum](https://login.xyz)

The submission is two-fold:

- Mainly a protocol flow diagram [Diagram source](./sequence_diagram.txt) heavily inspired by the one in [Auth0 blog post](https://auth0.com/blog/sign-in-with-ethereum-siwe-now-available-on-auth0/)

![Diagram](./sequence_diagram.png) 

- An example app in [app](./app) deployed on [cloudflare pages](https://oidc-siwe-app.pages.dev). The frontend code is a slight modification of auth0-samples/auth0-vue-samples of which this repo is a fork. In the app the use of Spruce https://oidc.login.xyz/ is heavily abstracted by auth0 integration.


One of original goal was to replace the auth0 OIDC provider or the SIWE provider with self-hosted alternative.

Reference 
- https://auth0.com/docs/authenticate/login/redirect-users-after-login
