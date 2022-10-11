# tailwindcss-custom-test

Teste de configuração do tailwindcss manualmente sem framework.

```
git clone https://github.com/rg3915/tailwindcss-custom-test.git
cd tailwindcss-custom-test

nvm use 18.3.0

npm init
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

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

