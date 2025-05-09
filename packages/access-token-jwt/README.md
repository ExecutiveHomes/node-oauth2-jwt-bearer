# access-token-jwt

This package is an EH internal published fork of access-token-jwt from node-oauth2-jwt-bearer.

This is done because they treat this package as internal themselves. Why? Who knows!

Modifications: 
- Stole errors.ts from oath2-bearer package to not need to also publish that one
- Added scripts/version to package.json
- This README

Verfies and decodes Access Token JWTs loosley following [draft-ietf-oauth-access-token-jwt-12](https://tools.ietf.org/html/draft-ietf-oauth-access-token-jwt-12)
