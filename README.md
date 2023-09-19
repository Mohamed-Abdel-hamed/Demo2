
# Api JWT
# Project Description
A program that uses only JWT technology
The technology with which it was written is
 Asp.NetCore MVC
  ## The packages used
### Microsoft.AspNetCore.Authentication.JwtBearer
### Microsoft.AspNetCore.Authentication.OpenIdConnec
### Microsoft.AspNetCore.Identity.EntityFrameworkCore
### Microsoft.EntityFrameworkCore
### Microsoft.EntityFrameworkCore.Design
### Microsoft.EntityFrameworkCore.SqlServer
### Microsoft.EntityFrameworkCore.Tools
### Microsoft.VisualStudio.Web.CodeGeneration.Design
### System.IdentityModel.Tokens.Jwt
## What is JSON Web Token?
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

Although JWTs can be encrypted to also provide secrecy between parties, we will focus on signed tokens. Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties. When tokens are signed using public/private key pairs, the signature also certifies that only the party holding the private key is the one that signed it.
To learn more about this tool,see here
https://jwt.io/introduction
