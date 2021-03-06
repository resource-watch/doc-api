# Documentation of RW API

To see the documentation, you access to:

[https://resource-watch.github.io/doc-api](https://resource-watch.github.io/doc-api)

# Requirements

- Ruby
- Bundler gem

# Installation and usage

## Ruby version

Please ensure that you are using the correct version of Ruby - this project requires Ruby version `2.4.1`.

It is recommend to use `rvm` to manage different versions of Ruby in your development environment. You can find [here instructions on how to install `rvm`](https://rvm.io/rvm/install).

## Installing dependencies

To install dependencies, use:

```bash
bundle install
```

To run the application server, use:

```bash
bundle exec middleman server
```

# Deploying to production

```bash
deploy.sh
```

# Contribution guide

You have set up the documentation project and are ready to contribute? Great, here are some tips to help you get started!

## The basics

- You'll find the user docs in the `source/includes/api` folder and the developer docs in the `source/includes/dev` folder.
- Each section of the API has its own file, roughly matching individual microservices. Looking at the URL you are trying to document will help you determine where your contribution should go.
- When it comes to documentation style (how you format your text or where do you place it in the document), odds are that something similar has already been done on another section. Before you start typing away, have a look at other sections and look for inspiration or copy-paste opportunities. They will both save you time and help the docs stay consistent in style and format.
- HTML elements like <aside> can be used but should be saved only for important notices or other info that cannot be communicated using the standard markdown structure.
- Use a spell checker.

## Guidelines

- Keep in mind that this documentation is used for Resource Watch, Aqueduct and Global Forest Watch - each of these projects will have it's own `/source/index-<project initials>.html.md`
- Contrary to what you may believe, Markdown rendering is not an exact science. Do test your changes by running the app server locally and checking the end result on the browser. Markdown preview tools output is known to be different from the HTML generated by this tool.


# Credits

Created with slate project:

<a href="q" target="_blank"><img src="https://raw.githubusercontent.com/lord/img/master/logo-slate.png" alt="Slate: API Documentation Generator" width="226"></a>


