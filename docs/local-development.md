# Local development for `NotifyNL`

This package is one of the dependencies used by `notifications-admin`.

For local development of `admin`, make sure to point `admin` to the local path of this package. For this, add to `admin` `package.json` the following:

```
`"govuk-frontend": "file:///replace_with_absolute_path_to/govuk-frontend/package/",
```

## Making changes

After you made change(s) and want to test it in `admin`, you need to build the package. In the root of the repo, run `npm run build:package`. Once the package is built, you can use it in the `admin`.
