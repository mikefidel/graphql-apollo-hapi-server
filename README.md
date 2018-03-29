# graphql-apollo-hapi-server

### [ In Development ] GraphQL backend to service requests for data contained on public and private NDEx servers.

At the moment this application is intended as a proof-of-concept. It is based on the Apollo 
stack, specifically its HAPI server varient.  HAPI was chosen because it appears to be the
server-of-choice by commercial and financial companies for its built-in robust security.
HAPI also has a strong and growing community of developer/contributors.

There are competing design choices, such as implementing a serverless architecture such as Amazon's
AWS Lambda service. There is also the question of using Javascript instead of the programming 
language NDEx REST servers are based - i.e. Java. Javascript runs as a single thread, and may be
and inappropriate platform to build a production GraphQL platform upon. Hopefully, 
Impediments and deficiencies will be revealed during it's early development stage.

Summary: This is a learning platform from which it is hoped a production version of this application may 
eventually emerge.

