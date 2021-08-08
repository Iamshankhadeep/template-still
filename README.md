# Remotion still image

<p align="center">
  <a href="https://github.com/remotion-dev/logo">
    <img src="https://github.com/remotion-dev/logo/raw/main/withtitle/element-0.png">
  </a>
</p>

[![Deploy to DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/remotion-dev/template-still/tree/main)

## Commands

**Start Preview**

```console
npm run dev
```

**Render still image**

```console
npm run render
```

**Upgrade Remotion**

```console
npm run upgrade
```

## Server

You can run a server that serves dynamic images based on it's URL. Run

```console
npm run server
```

And then visit `http://localhost:8000/PreviewCard.png?title=Hello+World` in your browser to render an image.

- Specify the ID of the composition you want to render after the `/`. You can edit the compositions in `src/Video.tsx`.
- Add either a `.png` or a `.jpeg` extension depending on which image format you want.
-

### Deploy to Heroku

If you want to deploy this project to Heroku, you need to add the [Puppeteer Buildpack](https://github.com/jontewks/puppeteer-heroku-buildpack) first. Go to the settings of your Heroku app and under `Buildpacks`, add `https://github.com/jontewks/puppeteer-heroku-buildpack.git` as a buildpack, **then reorder the buildpacks so that the Puppeteer buildpack is first.**

## Docs

Get started with Remotion by reading the [fundamentals page](https://www.remotion.dev/docs/the-fundamentals).

## Issues

Found an issue with Remotion? [File an issue here](https://github.com/remotion-dev/remotion/issues/new).

## License

Notice that for some entities a company license is needed. Read [the terms here](https://github.com/remotion-dev/remotion/blob/main/LICENSE.md).
