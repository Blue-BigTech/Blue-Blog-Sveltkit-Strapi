# SvelteKit and strapi.io website

``` bash
$ npm run setup
```

### sapper

``` bash
$ cd sapper
$ npm ci
$ npm run dev
```

### SvelteKit (not runable yet)

``` bash
$ cd sveltekit
$ npm ci
$ npm run dev
```

### strapi

Please run `npm run setup` before you setup strapi, to create a suitable `.env` file.

```bash
 $ npm run setup
 $ cd strapi
 $ npm ci
 $ npm run build
 $ npm run dev
```

For your information: I duplicate strapis `npm run develop` to a `npm run dev` command,
because many other frameworks start with `npm run dev`.

Strapi installation was created with the `--quickstart` option, for now it uses a sqlite database.
