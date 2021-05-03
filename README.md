# CSS Wiki

This is the wiki for computer science students at UWindsor

It is built using [Docusaurus 2](https://v2.docusaurus.io/) 

## Installation Packages

```console
yarn install
```

## Local Development

```console
yarn start
```

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

## Build

```console
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment a copy to github pages

1) Make sure you're in the right directory XD
2) Edit the docusaurus.config.js file to the following:
  - change 'url' to your url
  - change 'baseUrl' to '/'
3) Run the following command:
  - if on Windows (powershell) run this:
  ```console
    cmd /C 'set "GIT_USER=<Your Github username" && yarn deploy'
  ```
  - if on Linux run this:
  ```console
    GIT_USER=<Your Github username> yarn deploy
  ```
4) Go to https://github.com/<Your Github username>/Wiki/settings/pages and set active

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
