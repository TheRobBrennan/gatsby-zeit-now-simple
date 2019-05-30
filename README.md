# Welcome

This project has been created to demonstrate how easy it is to develop and deploy a [Gatsby](https://www.gatsbyjs.org) project using [ZEIT Now](https://zeit.co/now).

You can view the [demo](https://gatsby-zeit-now-simple.therobbrennan.now.sh) at [https://gatsby-zeit-now-simple.therobbrennan.now.sh](https://gatsby-zeit-now-simple.therobbrennan.now.sh)

This project assumes you have the [ZEIT Now CLI](https://zeit.co/download) tool installed on your machine - available at [https://zeit.co/download](https://zeit.co/download)

## Local development

To simulate the Now platform locally and run your project:

```sh
// The ZEIT Now CLI needs to be invoked this way. You will never call the now-dev script directly.
$ now dev

> Now CLI 15.2.1-canary.4 dev (beta) — https://zeit.co/feedback/dev
> Setting up 1 Builder
> Success! Builder setup complete
⠀
View GraphiQL, an in-browser IDE, to explore your site's data and schema
⠀
  http://localhost:63312/___graphql
⠀
Note that the development build is not optimized.
To create a production build, use npm run build
⠀
info ℹ ｢wdm｣:
info ℹ ｢wdm｣: Compiled successfully.

 WAIT  Compiling...18:58:26
⠀
info ℹ ｢wdm｣: Compiling...
 DONE  Compiled successfully in 58ms18:58:26
⠀
info ℹ ｢wdm｣:
info ℹ ｢wdm｣: Compiled successfully.

^C
> Stopping `now dev` server

```

See [https://zeit.co/docs/v2/development/basics/](https://zeit.co/docs/v2/development/basics/) for more details on [Development Basics](https://zeit.co/docs/v2/development/basics/).

## Deploy to ZEIT Now

To deploy this project to ZEIT Now:

```sh
$ now

> Deploying ~/repos/gatsby-zeit-now-simple under therobbrennan
> Using project gatsby-zeit-now-simple
> Synced 1 file (6.86KB) [573ms]
> https://gatsby-zeit-now-simple-1i8d2boos.now.sh [v2] [831ms]
┌ package.json        Ready               [1m]
├── 1-5e65615471e89e7a9dd5.js (17.77KB)
├── 404.html (10.03KB)
├── 404/index.html (10.01KB)
├── chunk-map.json (378B)
├── component---src-pages-404-js-3561fb60fa9f3ab9dca6.js (3.52KB)
└── 43 output items hidden
> Ready! Aliased to https://gatsby-zeit-now-simple.therobbrennan.now.sh [in clipboard] [1m]

```

See [https://zeit.co/docs/v2/deployments/basics/](https://gatsby-zeit-now-simple.therobbrennan.now.sh) for more details on [Deployment Basics](https://gatsby-zeit-now-simple.therobbrennan.now.sh)

To run these scripts, simply run `npm run <script_name>` at the root level of this project.

Original tutorial available at [https://zeit.co/guides/deploying-gatsby-with-now](https://zeit.co/guides/deploying-gatsby-with-now)

## BONUS: ZEIT Now examples

Did you know that if you run `now init` you can use any of the examples at [https://github.com/zeit/now-examples](https://github.com/zeit/now-examples) to spin up a new project quickly?

One more thing...You'll notice that there is an example in there for creating an [Advanced MDX-deck](https://github.com/zeit/now-examples/tree/master/mdx-deck-advanced) - an example created by the author of this repo.

<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby's default starter
</h1>

Kick off your project with this default boilerplate. This starter ships with the main Gatsby configuration files you might need to get up and running blazing fast with the blazing fast app generator for React.

_Have another more specific idea? You may want to check out our vibrant collection of [official and community-created starters](https://www.gatsbyjs.org/docs/gatsby-starters/)._

## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI to create a new site, specifying the default starter.

    ```sh
    # create a new Gatsby site using the default starter
    gatsby new my-default-starter https://github.com/gatsbyjs/gatsby-starter-default
    ```

1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```sh
    cd my-default-starter/
    gatsby develop
    ```

1.  **Open the source code and start editing!**

    Your site is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `my-default-starter` directory in your code editor of choice and edit `src/pages/index.js`. Save your changes and the browser will update in real time!

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

3.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

4.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

5.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

6.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

7.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

8.  **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.org/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

9.  **`LICENSE`**: Gatsby is licensed under the MIT license.

10. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

11. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

12. **`README.md`**: A text file containing useful reference information about your project.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

## 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/gatsbyjs/gatsby-starter-default)

<!-- AUTO-GENERATED-CONTENT:END -->
