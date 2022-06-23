# RevealJS Template

![Logo mashup](public/logo.png)

To use, either clone this repo, or run

```shell
$ npm init vite revealjs-template
```

and select the `vanilla` framework.

## Development

To run the development server and see updates in realtime,
head into `package.json`, and press the `debug` contextual
button placed by vscode above the `"scripts"` section (or
press CMD+SHIFT+P, type `npm`, and select `Debug NPM script).

Choose the `dev` option, and vite should spin up a localhost
server on which you can view the presentation, with hot reload
on file save.

Assets are placed in the `public` folder, and referred to in
`index.html` via their relative path with `public` as the root.

## Production

To convert the presentation into a static site, follow the 
development steps but then select `build`. This creates a
bundle in a folder called `dist`. We can preview this site
by choosing the `preview` npm option, again from the 
command palette. 