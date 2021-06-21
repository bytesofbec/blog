---
template: BlogPost
path: /creating-a-blog-using-gatsbyjs
date: 2021-06-15T14:56:55.002Z
title: Creating A Blog Using GatsbyJS
thumbnail: /assets/gatsby.png
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/v7QAljPf4UA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Gatsby

### What is GatsbyJS?

Gatsby is an open-source static website generator (SSG) based on the frontend development framework React and makes use of Webpack and GraphQL technology. It can build static sites that are progressive web apps, follow the latest web standards, and are optimized for speed and security.

I have been using GatsbyJS for a while now and I find it really easy to use and but at the same time it almost has everything that I'm looking for.

## Let's start building it

### Gatsby CLI

Install the Gatsby CLI globally by running the command below.

```
npm install -g gatsby-cli@3.3.0
```

Check that you have the correct version installed by running the command below. You should be on v3 or newer.

```shell
gatsby --version
```

Run `gatsby new` to create an app using the theme you want. For this, I am gonna be using [gatsby-casper](https://www.gatsbyjs.com/starters/scttcper/gatsby-casper) theme.

```
gatsby new blog https://github.com/scttcper/gatsby-casper
```

Once the installation is complete, we'll run the `cd blog` command which will take us to the location of our project file.

```
cd blog
```

Then we'll run `gatsby develop` that will start running on the local machine.

check out your “blog” app at `http://localhost:8000`.

```
gatsby develop
```

This is how it would look like, you can then edit it and start adding the posts.

![](/assets/gatsby-theme.gif)
