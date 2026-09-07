# Prose Einstein — published package index

`packages.json` names the current version of the **Prose Einstein** package, the extension
that connects [Prose](https://github.com/TheRadicalOnes/prose)'s AI Actions to Salesforce's
own Models API in orgs with Einstein Generative AI. It is served through GitHub Pages and
read by the Prose Setup page's Install button and by Prose's install tooling.

The package's source lives in the Prose repository, under `force-app/prose-einstein/`.
Releasing a new version means building it there and updating the `packageId` in this file.
