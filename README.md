# tailwindcss-course

Curso de tailwindcss com [Tiago Matos](https://www.youtube.com/watch?v=1eLaBow7Zbo&list=PLcoYAcR89n-r1m-tMfV4qndrRWpT_rb9u).

Estou usando [nvm](https://github.com/nvm-sh/nvm) para escolher a versão do Node.

Meu [gist nvm](https://gist.github.com/rg3915/6fad3d19f2b511ec5da40cef5a168ca5).

```
git clone https://github.com/rg3915/tailwindcss-custom-test.git
cd tailwindcss-custom-test

nvm use 18.3.0

npm init
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Instalação feita com [Tailwind CLI](https://tailwindcss.com/docs/installation).


Veja a configuração de [src/input.css](src/input.css) e [tailwind.config.js](tailwind.config.js).


### Build

```
npx tailwindcss -i ./src/input.css -o ./dist/output.css
```

## Rodando a app

Usei [live-server](https://www.npmjs.com/package/live-server).

```
npm install -g live-server
```

Run

```
live-server
```

## Links

https://www.creative-tim.com/learning-lab/tailwind-starter-kit/documentation/quick-start

https://vueschool.io/articles/vuejs-tutorials/composing-layouts-with-vue-router/

