# GitOps interview

Today you're working on a new platform for a client. The client wants everything
in GitOps for business continuity reasons. Your task today is to deploy a client
application - a petshop - which needs PostgreSQL and needs a connection string
to connect to said PostgreSQL.

There's already two pieces of infrastructure deployed:
- Cloud-native PostgreSQL (CNPG)
- Sealed secrets operator

The image of the app to be deployed is: docker.io/michielboekhoff/petshop-dotnet:1.0.0