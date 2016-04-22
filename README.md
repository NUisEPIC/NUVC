# NUVC Website

You need:

- Gulp
- NPM
- Nodejs

To get started:

```
~ $ npm i
... (installs packages)

~ $ gulp serve
... (runs tasks)
Started connect web server on http://localhost:9999

```

Now navigate your world wide web browser to that there uniform resource locator.

To build for production:

```
~ $ gulp
... (runs build tasks)
[HH:MM:SS] Finished 'build' after <some number> ms
```

Now everything you need will be in the `dist` directory. You can copy the contents
of that directory directly to the server to update the live site. Make sure
to test it first using your browser.

