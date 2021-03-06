# Documentation for Cloudflare Page Rules within `openactive.io`

Cloudflare Page Rules in use on the `openactive.io` domain are documented within this repository. This documentation must be updated to match the latest configuration for any changes made to Cloudflare Page Rules.

## Contribution

New Cloudflare Page Rules may be proposed via a PR to this repository. Please note that due to their cost the use of Cloudflare Page Rules should be minimised, and where possible [Wordpress Redirection](https://github.com/openactive/website-redirection) should be used instead.

## Cloudflare Page Rule documentation

![Cloudflare Page Rules](cloudflare-page-rules.png)

1. Ensures that the JSON-LD version the OpenActive Activity List is maximally cached, to minimise downtime.
2. Provides a redirect for all static assets previously hosted at the `www` subdomain (noting that the Wordpress Redirection Plugin does not handle binary static assets such as images).
3. A Gladstone instructional video references "openactive.io/programmes" and does not specify `www`. This redirect ensures that this reference will still resolve.
