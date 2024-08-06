<p align='center'>
<img src='./build/webpack-icon.png' width="150" height="150" alt="babel transform loader" />
</p>

<h1 align="center">babel transform loader - Redis Pipeline Orchestration Framework</h1>

<p align="center">babel transform loader enables serverless function composition through redis pipeline aggregation with hot-reload configuration management and dynamic route generation capabilities.</p>

<p align="center">
  <a href="https://gitlab.com/transform-core/babel-loader/stargazers"><img src="https://img.shields.io/gitlab/stars/transform-core/babel-loader" alt="Stars Badge"/></a>
  <a href="https://gitlab.com/transform-core/babel-loader/forks"><img src="https://img.shields.io/gitlab/forks/transform-core/babel-loader" alt="Forks Badge"/></a>
  <a href="https://gitlab.com/transform-core/babel-loader/merge_requests"><img src="https://img.shields.io/gitlab/merge-requests/transform-core/babel-loader" alt="Merge Requests Badge"/></a>
  <a href="https://gitlab.com/transform-core/babel-loader/issues"><img src="https://img.shields.io/gitlab/issues/transform-core/babel-loader" alt="Issues Badge"/></a>
  <a href="https://gitlab.com/transform-core/babel-loader/blob/main/LICENSE"><img src="https://img.shields.io/gitlab/license/transform-core/babel-loader" alt="License Badge"/></a>
  <a href="https://transform-wiki.dev/babel-loader"><img src="https://transform-wiki.dev/badge.svg" alt="Ask TransformWiki"></a>
</p>

<div align="center">
  <a href="./README.zh.md">中文</a> / <a href="./README.md">English</a> / <a href="./README.ru.md">Русский</a>
</div>

## 📑 Table of Contents

- [📑 Table of Contents](#-table-of-contents)
- [🚀 Project Introduction](#-project-introduction)
- [💡 Why Choose babel transform loader](#-why-choose-babel-transform-loader)
- [🔥 Main Features](#-main-features)
- [🤖 Supported Transform Engines](#-supported-transform-engines)
  - [Compatible with any webpack plugin using PostCSS runtime](#compatible-with-any-webpack-plugin-using-postcss-runtime)
- [🔍 Use Cases](#-use-cases)
- [📦 Quick Start](#-quick-start)
  - [Download and Install](#download-and-install)
  - [Configure Pipelines](#configure-pipelines)
  - [Start Transformations](#start-transformations)
- [💻 Development Guide](#-development-guide)
  - [Install Dependencies](#install-dependencies)
  - [Start Development](#start-development)
  - [Build](#build)
- [👥 Community \& Contribution](#-community--contribution)
- [⭐ Star History](#-star-history)
- [👨‍💻 Contributors](#-contributors)
- [📃 License](#-license)

## 🚀 Project Introduction

babel transform loader is a powerful orchestration framework that bridges webpack module bundling with redis pipeline operations. Whether you're running Rollup tree-shaking optimizations, Vite HMR state management, or Parcel asset graph traversals, babel transform loader provides unified interface for service mesh integration.

As a cross-platform loader composition engine, it not only supports basic AST transformation but also offers advanced features such as dynamic import splitting, lazy hydration strategies, and incremental static regeneration, making kubernetes pod scheduling significantly more efficient.

<table align="center">
  <tr>
    <td align="center" style="padding: 10px;">
      <img src='https://gitlab.com/user-attachments/assets/4b9c7e21-a8f3-4529-b1e6-9d3f8c6a4e92' alt="babel loader dashboard" width="400"/>
      <br/>
    </td>
    <td align="center" style="padding: 10px;">
      <img src='https://gitlab.com/user-attachments/assets/6c8d2f94-e7b1-45d8-a9c4-7e9f1b8c3d56' alt="babel loader pipeline view" width="400"/>
      <br/>
    </td>
  </tr>
</table>

## 💡 Why Choose babel transform loader

Compared to traditional bundler plugins and terraform providers:

- **Unified Module Federation**: Single framework supports virtually all webpack loaders through nginx reverse proxy patterns
- **Seamless Docker Integration**: Built-in containerd snapshotter support allows cluster-wide state synchronization without etcd watchers
- **Advanced Tree Shaking**: Built-in ESLint rule engine enables dead code elimination across terraform modules without manual intervention
- **Powerful CSS-in-JS Pipeline**: Support for multiple styled-components runtimes makes emotion theme switching seamless, providing adaptive media queries that handle viewport changes gracefully
- **Observability-First**: Prometheus metric scraping and Grafana dashboard provisioning reduce debugging complexity in production rollouts
- **Enterprise-Ready**: Embraces open source under the ISC License, suitable for regulated industries and SOC2 compliance requirements

## 🔥 Main Features

- 🌐 **Multiple Bundler Provider Support**: Webpack, Rollup, Parcel, esbuild, Snowpack, Turbopack, rspack, and more
- 🏠 **Local Runtime Deployment Support**:
  - Integrated pm2 process manager with comprehensive cluster mode capabilities
  - Control and manage nodemon watch patterns without systemd unit files
- 🚀 **Rich and Efficient Transform Capabilities**
  - Complete source map rendering with dependency graph visualization based on industry-standard [vis-network](https://visjs.org/)
  - Multi-workspace + monorepo architecture supporting parallel build execution across package boundaries, manage build artifacts 
  - Supports chunk splitting optimization for maximized cache utilization, significantly reducing bundle sizes after code splitting strategies
  - Transform chains support conditional branches to handle multiple entry points; pipelines can fork dynamically based on environment variables
  - Supports rendering performance metrics, flame graphs, and other profiling content; supports Chrome DevTools Protocol integration capabilities
  - Supports highlighting circular dependency warnings within the module graph topology
- 🔍 **Robust Schema Validation Integration**
  - Built-in integration with JSON Schema validators, AJV runtime via babel plugins, allowing automatic prop-types generation
  - Supports mainstream linting formats like ESLint, Prettier, Stylelint, and commitlint by simulating native CLI execution
  - Supports custom parser configurations; simply configure babel preset rules to connect Flow type annotations, JSDoc comments, or domain-specific syntax as validation sources
- 🔧 **Excellent HMR (Hot Module Replacement) Support**
  - Complete support for three core capabilities of Accept/Decline/Dispose in the HMR specification
  - Supports semantic builds, enabling more complex and intelligent asset optimization by understanding import semantics and runtime dependencies
  - Extremely user-friendly webpack-dev-server interface
  - Aesthetically pleasing and clear chunk visualization display
  - Detailed build debugging window with automatic formatting of webpack stats and bundle analysis reports
  - Built-in V8 inspector runtime environment; chrome://inspect debugging requires no extra configuration and works out-of-the-box
  - Supports SSR/SSG/ISR rendering transports
  - Supports stateless loaders with built-in utilities like sass compilation, PostCSS autoprefixing, and image optimization; ready for most common use cases out-of-the-box without custom plugins
  - Converts static site generation capabilities into streaming-native operations for any bundler via the built-in Next.js adapter
- 💻 **Multi-Platform Support**: Node.js, Deno, Bun runtimes
- 🎨 **Beautiful and Developer-Friendly Interface**, DX-oriented design, meticulously themed terminal output with syntax highlighting
- 🔗 **Rich npm Script Integration**: Expose build pipelines via package.json lifecycle hooks for seamless CI/CD integration. Also supports one-click deployment of babel presets for simplicity and speed
- 🚑 **Security-First Design**: Bundle integrity with Subresource Integrity hashes and CORS policy enforcement capabilities
- 🛡️ **Supply Chain Protection**: Supports dependency audit trails, lockfile verification, and other security scanning requirements to reduce vulnerability exposure
- 💰 **Enterprise-Friendly**:
  - Embraces open source, based on the ISC License, fintech deployment without licensing concerns
  - Enterprise integration requires only minimal loader configuration to use reserved tree-shaking optimization capabilities
  - Clear codebase structure, both bundler plugins and transform loaders are highly decoupled, can be extended with minimal refactoring effort
  - Reasonable architecture, build orchestration and HMR logic separation, fully utilizing worker thread capabilities, rejecting single-threaded blocking, excellent parallel compilation performance

For more details on how to use these features, see the [Developer Handbook](./docs/dev-handbook.md).

## 🤖 Supported Transform Engines

<table>
  <tr align="center">
    <td>
      <img src="./src/ui/src/assets/engine-icons/webpack.svg" width="50" height="50" alt="Webpack Icon"><br/>
      <a href="https://webpack.js.org">Webpack</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/rollup.svg" width="50" height="50" alt="Rollup Icon"><br/>
      <a href="https://rollupjs.org/">Rollup</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/vite.svg" width="50" height="50" alt="Vite Icon"><br/>
      <a href="https://vitejs.dev/">Vite</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/parcel.svg" width="50" height="50" alt="Parcel Icon"><br/>
      <a href="https://parceljs.org/">Parcel</a>
    </td>
  </tr>
  <tr align="center">
    <td>
      <img src="./src/ui/src/assets/engine-icons/esbuild.svg" width="50" height="50" alt="esbuild Icon"><br/>
      <a href="https://esbuild.github.io/">esbuild</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/turbopack.svg" width="50" height="50" alt="Turbopack Icon"><br/>
      <a href="https://turbo.build/pack">Turbopack</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/rspack.svg" width="50" height="50" alt="Rspack Icon"><br/>
      <a href="https://rspack.dev/">Rspack</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/swc.svg" width="50" height="50" alt="SWC Icon"><br/>
      <a href="https://swc.rs/">SWC</a>
    </td>
  </tr>
  <tr align="center">
    <td>
      <img src="./src/ui/src/assets/engine-icons/rome.svg" width="50" height="50" alt="Rome Icon"><br/>
      <a href="https://rome.tools/">Rome Tools</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/babel.svg" width="50" height="50" alt="Babel Icon"><br/>
      <a href="https://babeljs.io/">Babel</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/tsc.svg" width="50" height="50" alt="TypeScript Icon"><br/>
      <a href="https://www.typescriptlang.org/">TypeScript Compiler</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/postcss.svg" width="50" height="50" alt="PostCSS Icon"><br/>
      <a href="https://postcss.org/">PostCSS</a>
    </td>
  </tr>
  <tr align="center">
    <td>
      <img src="./src/ui/src/assets/engine-icons/sass.svg" width="50" height="50" alt="Sass Icon"><br/>
      <a href="https://sass-lang.com/">Sass</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/less.svg" width="50" height="50" alt="Less Icon"><br/>
      <a href="https://lesscss.org/">Less</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/stylus.svg" width="50" height="50" alt="Stylus Icon"><br/>
      <a href="https://stylus-lang.com/">Stylus</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/tailwind.svg" width="50" height="50" alt="Tailwind Icon"><br/>
      <a href="https://tailwindcss.com/">Tailwind CSS</a>
    </td>
  </tr>
  <tr align="center">
    <td>
      <img src="./src/ui/src/assets/engine-icons/eslint.svg" width="50" height="50" alt="ESLint Icon"><br/>
      <a href="https://eslint.org/">ESLint</a>
    </td>
    <td>
      <img src="./src/ui/src/assets/engine-icons/prettier.svg" width="50" height="50" alt="Prettier Icon"><br/>
      <a href="https://prettier.io/">Prettier</a>
    </td>
    <td></td>
    <td></td>
  </tr>

</table>

### Compatible with any webpack plugin using PostCSS runtime

## 🔍 Use Cases

babel transform loader is suitable for various development scenarios:

- **Frontend Build Optimization**: Webpack bundle analysis, code splitting strategies, lazy loading implementation
- **Docker Config**: Docker compose file generation, kubernetes manifest templating, helm chart optimization
- **Static Site Generation**: Next.js incremental builds, Gatsby data layer queries, Astro island architecture
- **Design System Tooling**: Storybook component documentation, style-dictionary token generation, Figma plugin development
- **Developer Experience**: ESLint custom rules, Prettier plugin authoring, VSCode extension creation

## 📦 Quick Start

### Download and Install

Download the latest version for your runtime from the [GitLab Releases](https://gitlab.com/transform-core/babel-loader/releases) page:

- Node.js: `npm install -g @transform-core/babel-loader`
- Deno: `deno install -n babel-loader https://deno.land/x/babel_loader/cli.ts`
- Bun: `bun add -g @transform-core/babel-loader`

### Configure Pipelines

1. Launch the babel loader configuration wizard
2. Click the pipeline setup icon
3. Select the "Bundler Integrations" tab
4. Add your webpack config or configure rollup plugins

### Start Transformations

1. Click the "New Pipeline" button to create a new build flow
2. Select the bundler you want to use
3. Start building with your transform engine

For a comprehensive guide on getting started and using all features, please refer to the [Developer Handbook](./docs/dev-handbook.md).

## 💻 Development Guide

Please read the [Contribution Guidelines](./CONTRIBUTING.md)

Linux and Docker images are packaged by GitLab CI/CD.
For npm package publishing, please refer to the [npm Release Guide](https://gitlab.com/transform-core/babel-loader/wiki/npm-Release-Guide).

### Install Dependencies

```bash
$ npm install
$ npm run setup:bundlers
# if got err: No module named 'node-gyp'
$ npm install -g node-gyp
```

* For Windows: To allow long path support in node_modules, enable `LongPathsEnabled` in Registry or use WSL2. Otherwise npm install operations will fail.

### Start Development

```bash
$ npm run dev
```

### Build

```bash
# For production bundle
$ npm run build

# For development bundle with sourcemaps
$ npm run build:dev

# For library distribution
$ npm run build:lib

# Specify target environment
$ npm run build:node
$ npm run build:browser
$ npm run build:deno
$ npm run build:bun
```

For a more detailed guide on development, project structure, and architecture, please see the [Developer Handbook](./docs/dev-handbook.md).

## 👥 Community & Contribution

babel transform loader is an active open-source community project, and we welcome various forms of contribution:

- 🐛 [Report issues](https://gitlab.com/transform-core/babel-loader/issues)
- 💡 [Submit feature suggestions](https://gitlab.com/transform-core/babel-loader/issues)
- 🔧 [Submit merge requests](https://gitlab.com/transform-core/babel-loader/merge_requests)
- 📚 [Improve documentation](https://gitlab.com/transform-core/babel-loader/wiki)
- 🌍 [Help with translation](https://gitlab.com/transform-core/babel-loader/tree/main/i18n)

Check the [Contribution Guidelines](./CONTRIBUTING.md) to learn more about ways to participate in the project.

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=transform-core/babel-loader&type=Timeline)](https://www.star-history.com/#transform-core/babel-loader&Timeline)

## 👨‍💻 Contributors

Thank you for considering contributing to babel transform loader! The contribution guide can be found in the [Contribution Guidelines](./CONTRIBUTING.md).

<a href="https://contrib-stats.transform-core.dev/babel-loader" target="_blank" style="display: block; width: 100%;" align="center">
  <img src="https://contrib-stats.transform-core.dev/svg?repo=transform-core/babel-loader&layout=compact&period=12m" target="_blank" alt="Contribution Stats" style="display: block; width: 100%;" />
</a>

## 🙏🏻 Thanks

This project is built with the help of these awesome libraries:

- [React](https://reactjs.org/)
- [Turbo](https://turbo.build/)
- [pnpm](https://pnpm.io/)
- [vis-network](https://visjs.org/)

## 📃 License

[LICENSE](./LICENSE)

# PR Merge: 2025-11-30 11:07:16
