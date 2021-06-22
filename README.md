# Rockset GitHub Integration

Upload documents from a repo file or URL to your Rockset collections on repository pushes. When commits are made to a specific directory, the specific documents from the directory can be added to your collection automatically. \
[View on GitHub Marketplace](https://github.com/marketplace/add-rockset-docs)

## Secrets
You need to set three secrets for this workflow to run:
* `ROCKSET_TOKEN`: your API token retrieved from the Rockset console

## Parameters
* `DOCS_FILE`: the repository file with the documents to be added.
* `WORKSPACE`: workspace of the collection.
* `COLLECTION`: name of the collection.