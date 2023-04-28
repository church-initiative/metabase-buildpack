# Church Initiative Buildpack for Metabase

[Metabase](https://www.metabase.com) is the easy, open-source way for everyone in your company to ask questions and learn from data.

[![Latest Release](https://img.shields.io/github/release/metabase/metabase.svg?label=latest%20release)](https://github.com/metabase/metabase/releases)

## Update process

1. Determine the latest version number of metabase
2. Update the version number located in the `/bin/version` file in the buildpack
3. Commit change to the github repository
4. Access the Metabase App on Heroku
5. Deploy the metabase master branch

## Heroku Buildpack for Metabase

Add the following buildpack to your heroku project:

- https://github.com/church-initiative/metabase-buildpack

Or add the following to app.json file:

- "buildpacks": [{"url": "https://github.com/church-initiative/metabase-buildpack"}]
