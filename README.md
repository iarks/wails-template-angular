# README

## About

This is a sample wails template for Angular.

It is a vanilla wails template with an Angular project in the `frontend` directory and the following configurations added to `wails.json`.
The configurations are provided in https://wails.io/docs/guides/angular

```json
"frontend:build": "npx ng build",
"frontend:install": "npm install",
"frontend:dev:watcher": "npx ng serve",
"frontend:dev:serverUrl": "http://localhost:4200",
```

## Live Development

To run in live development mode, run `wails dev` in the project directory. This will run a Vite development server that will provide very fast hot reload of your frontend changes. If you want to develop in a browser and have access to your Go methods, there is also a dev server that runs on http://localhost:34115. Connect to this in your browser, and you can call your Go code from devtools.

## Building

To build a redistributable, production mode package, use `wails build`.
