# Sony 2002 Website Recreation

The 2002 Sony USA homepage, rebuilt in TypeScript, React, and Vite.

<img src="screenshot.png" width="780" alt="Recreated 2002 Sony USA homepage with the Sony masthead, welcome hero, and SEE, HEAR, PLAY, and SHOP columns.">

By [Robert Fernandez](https://robertfernandez.dev) ([robfernan](https://github.com/robfernan)). The GitHub homepage field is empty, GitHub Pages is disabled, and this repo has no deploy config, so run it locally.

## Run locally

Node.js `^20.19.0` or `>=22.12.0`, which is what Vite 8 requires.

```bash
npm install
npm run dev
```

`npm run dev` runs `vite dev` and prints a local URL. `npm run build` makes a production build, `npm run preview` serves it, and `npm run lint` runs ESLint.

`bun.lock` is committed as well: `bun install` and `bun run dev` use the same scripts.

## Scope

The page is the `/` route in [`src/routes/index.tsx`](src/routes/index.tsx).

- Masthead with the Sony logo, a search field, Global Sites, and USA
- Explore bar: Shop, Electronics, PlayStation, Online Games, Movies, TV & DVD, Music, and More of Sony
- Hero, with the PlayStation 2 "what's new" copy beside it (under the image on small screens)
- SEE, HEAR, PLAY, and SHOP panels: clipped corners, promo stills, and footer link rows
- Footer, including the "© 2002 Sony Corporation of America" line from the original page

Links are `#` anchors, and the search form stays on this page. Sony Style, PlayStation, Screenblast, and the other names are labels in the layout. Logo and promo images are in `public/assets/`. Colors and the Verdana stack are in `src/styles.css`.

`src/components/ui` comes with the TanStack Start template and sits outside this page.

## Stack

TypeScript, React, Vite, TanStack Start, and Tailwind CSS. Routes are files under `src/routes`.

## License

Code is [MIT](LICENSE), © 2026 Robert Fernandez.

Unofficial recreation. Sony, PlayStation, and the logos and promotional images belong to their owners.

If this early-2000s portal is your kind of web, a star helps other people find it.
