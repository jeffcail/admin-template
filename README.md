# admin-template

<a href="https://github.com/mazezen/admin-template/releases">
    <img src="https://img.shields.io/github/release/admin-template/releases.svg" alt="GitHub release">
  </a>
   <a href="https://github.com/mazezen/admin-template/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="license">
  </a>

Vue3 + typescript + pinia + Element Plus 后台通用管理系统模版。


## 安装步骤
```
git clone https://github.com/mazezen/admin-template
cd admin-template

npm install

npm run dev

npm run build
```

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```
