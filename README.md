# Prancing Ponies - A Band Website

This is a simple site meant to feature a cover band named **Prancing Ponies**.

This site is built with [Astro.build](https://astro.build). Please read the official docs for info on the framework.

## Install

To run this site locally, you must have an instance of node v18 or higher. Clone this repo and from the repo's top level directory, run:

```bash
npm install
```

and to run a local developmental server:

```bash
npm run dev
```

You may then visit the site at [localhost:4321](http://localhost:4321)

## Add/Edit Events

To add or edit an event, navigate to `events` directory.

```
|--Prancing-Ponies
|  |--src
|  |  |--content
|  |  |  |--events
```

Simply duplicate one of the markdown files to ensure all the necessary frontmatter is present. Replace the data for each field and set `published` to `true` to ensure that the event will be visible on the home page. Toggle `published` to `false` to remove the listing from the home page without deleting it. The event will still be accessible via its relevant url.

Be mindful naming the event file, as the name of the event will be (minus the '.md') will be the url path. eg `no-events.md` is reachable at [localhost:4321/events/no-events](#).

Event files must either be of file type `.md` or `.mdx`.
