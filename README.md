# lolife

for those who don't touch grass and don't know what's a shower.

## Inspiration

- Template for the plugin was taken from [Pengu's Vite plugin template](https://github.com/PenguLoader/PenguLoader/blob/v1.0.5/plugins/vite-theme).

## Development

### Prerequisites

- Node.js
- pnpm

### Setup

```sh
# clone and navigate to the repository if not done already
git clone https://github.com/Vexcited/lolife
cd lolife

# install dependencies
pnpm install
```

### Commands

| Command | Description |
| --- | --- |
| `pnpm dev` | Starts the development server. Don't forget to provide the path of the Pengu Loader plugins folder in the variable `PLUGINS_DIR` inside `vite.config.ts` so the plugin gets updated there automatically. |
| `pnpm build` | Builds the plugin into the `dist` directory, ready to be dragged into the Pengu's plugins folder. |
