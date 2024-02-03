# OEE-ExtendedDirectory

Add a brief description of this project here, in Markdown format.
It will be shown on the main page of the project's GitHub repository.

## Development

To work on this project in a scratch org:

1. [Set up CumulusCI](https://cumulusci.readthedocs.io/en/latest/tutorial.html)
2. Run `cci flow run dev_org --org dev` to deploy this project.
3. Run `cci org browser dev` to open the org in your browser.

Make sure your SF CLI is hooked up to csuextendedcampus since it's our devhub.
sf org login web --set-default-dev-hub --alias DevHub
cci org import DevHub PROD