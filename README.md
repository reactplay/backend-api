# backend-api

`ReactPlay` uses [NHost](https://nhost.io/) as the back-end service for,

- Database (PostgreSQL)
- Hasura based GraphQL platform
- Serverless APIs
- E-mail services.

This project enables ReactPlay's backend configurations for databases, GraphQL queries, serverless APIs using the NHost CLI tool. You can adjust schema, create/update tables, queries locally and finally can push it to the NHost cloud.

## How to get started?

- Clone this repository.
- Make sure you have `Git` and `Docker` installed.
- Install nhost-cli using the following command

```bash
sudo curl -L https://raw.githubusercontent.com/nhost/cli/main/get.sh | bash
```
- Change dirctory to `backend-api` and execute the following command,

```bash
nhost dev
```
- Now you will have the Hasura Client running locally on http://localhost:1337



