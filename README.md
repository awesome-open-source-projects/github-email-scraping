This tool helps you extract the email addresses of contributors from the commit history of any GitHub repository.

It can either clone the repository and extract the email data locally or use the GitHub Rest API to fetch only the commit history.

The latter option is recommended for massive repositories, as some have over 10k commits, and cloning them requires downloading a significant amount, possibly over 20 Gigabytes.

However, to use GitHub's REST API, you are limited to a dozen requests per hour; however, this limitation is not present when cloning repositories.
