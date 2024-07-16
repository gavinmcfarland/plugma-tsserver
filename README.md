# plugma-tsserver

Screenshot of error when using autocomplete for CodeMirror. I think it comes from line 11 of `tsserver.js`.


<img width="810" alt="Screenshot 2024-07-16 at 22 14 44" src="https://github.com/user-attachments/assets/aa783944-d004-44e0-a94c-ac2a5db7a514">

## Quickstart

This plugin was created with [Plugma](https://github.com/gavinmcfarland/plugma) using the [Svelte](https://svelte.dev/) framework.

### Requirements

- [Node.js](https://nodejs.org/en)
- [Figma desktop app](https://www.figma.com/downloads/)

### Develop and Import

1. Install the dependencies and watch for changes while developing:

   ```shell
   npm install
   npm run dev
   ```

2. Open the Figma desktop app and import the plugin:

   - Open a file in Figma.
   - Search for "Import plugin from manifest..." using the [Quick Actions](https://help.figma.com/hc/en-us/articles/360040328653-Use-shortcuts-and-quick-actions#Use_quick_actions) bar.
   - Choose the `manifest.json` file from the `dist` folder.

3. Manage `manifest` details from inside `package.json`.

### Preview

Open [http://localhost:\<port\>](http://localhost:3000) to preview your plugin in different browsers.

_Make sure the plugin is open in the Figma desktop app._

### Publish

Before publishing, make sure to create a build:

```
npm run build
```

Now you can publish the plugin from the Figma desktop app.

### Advanced

See [Plugma](https://github.com/gavinmcfarland/plugma) for further options.
