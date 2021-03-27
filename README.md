<p align="center">
  <a href="//tinkerun.netlify.app/">
    <img alt="Tinkerun" src="https://user-images.githubusercontent.com/1612364/112719665-f4056e00-8f34-11eb-85b7-8fcc7dc509fc.png" width="100" style="max-width:100%;"/>
  </a>
</p>
<h1 align="center">Tinkerun</h1>

<p align="center">
  A new way of Running <a href="//github.com/laravel/tinker">Tinker</a>. 
  Simplify the Web Artisan's workflow.
  inspired by <a href="//tinkerwell.app">Tinkerwell</a>
</p>

<p align="center">
<img width="100%" alt="screenshot" src="https://user-images.githubusercontent.com/1612364/112504654-f34ec980-8dc6-11eb-967e-f5c48c4f2af1.png">
</p>

### Download links
[Github Releases](//github.com/tinkerun/tinkerun/releases)

### Features

- [x] **Connections**: Quick connect to your app either locally, in production or in docker container etc;
- [x] **Snippets**: Manage the code snippets you have ran;
- [x] **Editor**: Run your terminal code via editor;
- [x] **Output**: Focus on the results you really care that terminal return;

### Next Features

- [ ] **Form mode**: Switch the editor to the form, so that you can modify your variable value via form, like an admin panel;
- [ ] **Other languages**: Now it's only support php-snippet, may be there is a way to run python,node.js,ruby code;
- [ ] **Web**: So that you can use it everywhere;
- [ ] **Dark mode**

## Tech Stack

* [Electron](https://www.electronjs.org/)
* [Lerna](https://lerna.js.org/) (Monorepo)

### Renderer

* [React](https://reactjs.org/)
* [jotai](https://github.com/pmndrs/jotai) (State manage)
* [Immer](https://immerjs.github.io/immer/)
* [Monaco Editor](https://microsoft.github.io/monaco-editor/)
* [Xterm.js](https://xtermjs.org/)
* [wouter](https://github.com/molefrog/wouter)
* [Evergreen](https://evergreen.segment.com/) (UI)
* [React Hook Form](https://react-hook-form.com/)
* [nanoid](https://zelark.github.io/nano-id-cc/)
* [React Intl](https://formatjs.io/docs/react-intl/)
* [Snowpack](https://www.snowpack.dev/) (build the renderer process code)

### Main

* [node-pty](https://github.com/microsoft/node-pty)
* [electron-store](https://github.com/sindresorhus/electron-store)
* [ncc](https://github.com/vercel/ncc) (build the main process code)

## Contributing to Tinkerun

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## Community

Join the [Tinkerun Discord](https://discord.gg/7XFV6dmsat)