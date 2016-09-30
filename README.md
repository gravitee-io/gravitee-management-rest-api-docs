# Management Rest API Docs

Source for Management Rest API Docs.

## How to Build

```
cd ~/Code
git clone git@github.com:gravitee-io/gravitee-management-rest-api-docs.git
cd api-docs
bundle install
DEPLOY_ENV=development
rake
```

## Adding an App

- Add the app's subdomain to the Rakefile. This will cause `rake` to pull docs from that app.
- Add the app's `include` file to `index.md`'s YAML frontmatter. This will cause the docs to be rendered on the page.
