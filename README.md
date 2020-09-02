<p align="center"><h1 align="center">
  netlify-plugin-snyk
</h1>

<p align="center">
  A Netlify Build plugin to find security vulnerabilities
</p>

<p align="center">
  <a href="https://www.npmjs.org/package/netlify-plugin-snyk"><img src="https://badgen.net/npm/v/netlify-plugin-snyk" alt="npm version"/></a>
  <a href="https://www.npmjs.org/package/netlify-plugin-snyk"><img src="https://badgen.net/npm/license/netlify-plugin-snyk" alt="license"/></a>
  <a href="https://www.npmjs.org/package/netlify-plugin-snyk"><img src="https://badgen.net/npm/dt/netlify-plugin-snyk" alt="downloads"/></a>
  <a href="https://github.com/snyk-labs/netlify-plugin-snyk/actions?workflow=CI"><img src="https://github.com/snyk-labs/netlify-plugin-snyk/workflows/CI/badge.svg" alt="build"/></a>
  <a href="https://codecov.io/gh/snyk-labs/netlify-plugin-snyk"><img src="https://badgen.net/codecov/c/github/snyk-labs/netlify-plugin-snyk" alt="codecov"/></a>
  <a href="https://snyk.io/test/github/snyk-labs/netlify-plugin-snyk"><img src="https://snyk.io/test/github/snyk-labs/netlify-plugin-snyk/badge.svg" alt="Known Vulnerabilities"/></a>
  <a href="./SECURITY.md"><img src="https://img.shields.io/badge/Security-Responsible%20Disclosure-yellow.svg" alt="Responsible Disclosure Policy" /></a>
</p>

# About

A Snyk Netlify build plugin to add to your Netlify website's pipeline and guard you from deploying static websites with known JavaScript vulnerabilities.

# Usage

How to add security controls to your website build pipeline in 3 easy steps?

1. **Add the plugin!**

   If you're using Netlify's UI, browse the _Plugins_ directory and add `netlify-plugin-snyk` to your website project. Or you can also declare the plugin via a `netlify.yoml` configuration file as follows:

   ```
   # netlify.toml
   [[plugins]]
   package = "netlify-plugin-snyk"
   ```

2) **Configure the Snyk API token**

   If you alreay have the Snyk CLI installed you can get the token via `snyk config get api` and add an entry in Netlify's [Environment variable settings page](https://app.netlify.com/sites/speak-easy/settings/deploys#environment) with variable name `SNYK_TOKEN`.

   To obtain a Snyk API token go to `https://app.snyk.io/account`.

3. **Deploy safely** 🐶

# Configuration

TBD

# Example

TBD

# Contributing

Please consult [CONTRIBUTING](./CONTRIBUTING.md) for guidelines on contributing to this project.
