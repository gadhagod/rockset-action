# Rockset GitHub Integration

Upload documents to your Rockset collections on repository pushes. \
[View on GitHub Marketplace](https://github.com/marketplace/add-rockset-docs)

## Secrets
You need to set three secrets for this workflow to run:
* `ROCKSET_TOKEN`: your API token retrieved from the Rockset console
* `DOCS_RAW_URL`: the URL to the documents to be added. To get the raw URL for a file in your repo, click the file and hit <kbd>raw</kbd>. This is the URL.
* `WORKSPACE`: workspace of the collection.
* `COLLECTION`: name of the collection.

## Configuration
You can have it run only on certain branches or paths by adding keys `branch` or `paths` to `push`.

***

Lots more coming soon.
