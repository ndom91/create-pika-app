> **DEPRECATED** - This was the init-cli for the original snowpack release.  
> There has been a rewrite which resulted in the currently supported [`create-snowpack-app`](https://github.com/snowpackjs/snowpack/tree/main/create-snowpack-app/cli).

# 📦✨ snowpack-init

Start a bundler-free [`Snowpack`](https://www.snowpack.dev) web application with a single command!

![Usage Gif](https://imgur.com/eoLXgYq.gif)

## 🛫 Quick Start

```js
npx snowpack-init awesome-new-app-directory
cd awesome-new-app-directory
npm run dev
```

The example application will then be available at [`localhost:5000`](http://127.0.0.1:5000)

## 💻 Usage

```js
Usage: npx snowpack-init --template [template] <project-name>

Options:
  -V, --version              output the version number
  -t, --template [template]  template choice (optional)
  -h, --help                 output usage information

Examples:
  $ npx snowpack-init --template app-preact my-new-app
  $ npx snowpack-init --template app-lit my-new-app
  $ npx snowpack-init my-new-app
```

## 🌲 Templates

1. `app-preact`

<img width="400px" src="https://github.com/ndom91/terminal-homepage/raw/develop/terminal.gif" align="right"></img>

Slimmed down version of [`terminal-homepage`](https://github.com/ndom91/terminal-homepage) built on the following stack:

- Snowpack
- Preact
- Preact-router
- Preact-emotion
- Typescript
- Babel
- ESLint
- Prettier

2. `app-vue`

<img width="500px" src="https://imgur.com/A2msrQA.png" align="right"></img>

- Snowpack
- Vue
- http-vue-Loader
- Basic todo list example
- Original Source: [glitch.me/pika-web-vue-httpvueloader](https://glitch.com/edit/#!/pika-web-vue-httpvueloader)
- Thanks: [`@thiagoabreu`](https://github.com/thiagoabreu)

3. `app-lit`

<img width="500px" src="https://imgur.com/FpyU0Eg.png" align="right"></img>

- Snowpack
- LitElement
- lit-html
- Basic To do List Example
- Thanks: [`@thepassle`](https://github.com/thepassle)

4. `app-typescript`

- Snowpack
- Typescript
- Babel
- ESLint
- PostCSS
- Thanks: [`@karlprieb`](https://github.com/karlprieb)

5. `Your next app` 😎

If you'd like to have your project included here, just open a PR and we'll take a look!

## 🚧 Contributing

1. Clone the repo  
   `git clone https://github.com/ndom91/snowpack-init.git snowpack-init`

2. Install the project  
   `cd snowpack-init && npm install`

To test execution of the binary:

3. Build the binary
   `npm run build`

4. Generate a test application
   `node pkg/dist-node/index.bin.js generated-test-app-name`

5. Fork, commit & push your changes, and then make a pull request back to this repository!

---

### 📝 Licence

[`MIT`](https://opensource.org/licenses/MIT)
