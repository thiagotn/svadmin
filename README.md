# svadmin

<p align="left">
  <a href="https://svadmin.io">
    <img alt="Current version badge" src="https://shields.io/badge/production-0.0.25-green">
  </a>
</p>

POC for the validation of github actions in a project with svelte-kit, docker and Kubernetes resources.

## TODO list

| Id | Item  | Status  |
|---|---|---|
| 1 | Pipeline Github Actions  | ✓ |
| 2 | Docker Image/Push  | ✓ |
| 3 | Docker Image, update version (from 0.0.1 to 0.0.2) | ✓ |
| 4 | Update files that uses app version | ✓ |
| 5 | Call ArgoCD to start delivery |  TODO |
| 6 | [Teams notification](https://github.com/marketplace/actions/notify-microsoft-teams)  |  TODO |

## About Svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/main/packages/create-svelte).

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.


## Docker

### Build Image

To build a docker image:

```bash
docker build -t svadmin .
```

### Run Image

To run the image:

```bash
docker run -p 3000:3000 svadmin
```


  
