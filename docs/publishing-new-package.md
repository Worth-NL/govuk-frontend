# Publishing and using new package

If you need to publish a new package (after making some changes and running `npm run build:package`) to be used by `notifications-admin`, do the following:

1. Copy the content of the `package` folder
1. Update `https://github.com/Worth-NL/govuk-frontend-package` with the copied content
1. Create a new release/tag for `https://github.com/Worth-NL/govuk-frontend-package`
1. Update `notifications-admin` to use the new tag for `govuk-frontend-package`