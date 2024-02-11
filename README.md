# Apache Website Template

This project contains a template website that aims to follow all the various required Apache Website Policies.

This template was generated using [Docusaurus](https://docusaurus.io/).

## Usage

You can directly copy from the root path of this template repository to your website repository.

> [!NOTE]
> TODO: Integrate it with [template support of Docusaurus](https://docusaurus.io/docs/api/misc/create-docusaurus#git-strategy).

Most of the configurations are inherited from Docusaurus https://docusaurus.io/docs/configuration.

Specificly, our template defines a few metadata fields to customize for every project:

```typescript
const projectName = "Template";
const mainRepoName = "apache-website-template";
const siteRepoName = "apache-website-template";
```

For example, Apache Fury can customize these fields as:

```typescript
const projectName = "Fury";
const mainRepoName = "incubator-fury";
const siteRepoName = "incubator-fury-site";
```

More placeholders and preset are under developed.

## Deploy

This template contains [a GitHub Actions workflow](.github/workflows/deploy.yml) to deploy the generated website content to the `asf-site` branch. It would work automatically, without any other ections required.
