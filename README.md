# CodeQL Query List
A daily updated list of CodeQL queries.  In every build of CodeQL, we generate a list of all the CodeQL queries along with which query suite they belong to and many other data points about the queries.  This repo is a simplified location to grab that list.

🚀 **View the list [here](./code-scanning-query-list.csv)**.

### Where is this data generated from?
The github/codeql repo outputs a list of CodeQL queries on each build as an artifact.  You can view that artifact by opening [this Actions page](https://github.com/github/codeql/actions/workflows/query-list.yml), then selecting the most recent run.  You'll see the query list as an artifact of the action run.  We're just trying to simplify it a bit with this repo.