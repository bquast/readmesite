# READMEsite

**READMEsite** is static site generator, that turns the `README.md` of any repository into a standalone website;
no files, configs or flags, just the command builds the site.

It converts a git repository's `README.md` file into a clean, single-page static website.
It's designed to be zero-configuration for the target repository and generates sites that are easy to deploy.

Additional markdown files (with the extension `.md) are also rendered, with a menu included in the footer.


## Usage

To use `readmesite`, run it using [npx](https://docs.npmjs.com/cli/v8/commands/npx):

```
npx readmesite
```

That's all! Just running that command will create your standalone website.
By default it will be placed in the same directory (the project folder).

## Themes

Themes can be set from local or remote CSS and HTML files, or directly from the [store](https://store.readme.site/):

```
npm readmesite --theme darkmode
```

For more info see the [themes page](/themes).


## Google Analytics

READMEsite can automatically include the Google Analytics javascript snippet with the supplies GA property ID:

```
npx readmesite --ga G-EK4J8D3VHC
```

For more info see the [analytics page](/analytics).
