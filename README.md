# README

## About

Wails template for Nextjs v15 with tailwindcss v4.

You can configure the project by editing `wails.json`. More information about the project settings can be found
here: https://wails.io/docs/reference/project-config

## New Project

You can create a new wails project using:

```
wails init -n "Your Project Name" -t https://github.com/kairo913/wails-nextjs-tailwind-template
```

## Live Development

To run in live development mode, run `wails dev` in the project directory. This will run a Vite development
server that will provide very fast hot reload of your frontend changes. If you want to develop in a browser
and have access to your Go methods, there is also a dev server that runs on http://localhost:34115. Connect
to this in your browser, and you can call your Go code from devtools.

## Building

To build a redistributable, production mode package, use `wails build`.
