# FIRELINE — React framework

Purple-to-black dashboard built with React and Vite. Includes React Bits Topography at scale 1.3 as a subtle animated background and SpotlightCard effects on the summary cards. The sidebar is collapsible and resizable from 15–25% on desktop.

## View without npm
Open `dist/index.html` directly in a browser. This is a bundled single-file React app. Internet is needed only for Google Fonts.

## Develop
Install Node.js LTS, restart the terminal, then run:

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
```

The build produces a standalone `dist/index.html`.

React Bits components are in `src/components/reactbits/Topography` and `src/components/reactbits/SpotlightCard`. They are sourced from https://reactbits.dev/ and remain in their original component folders.

Title screen: click FIRELINE; the title transitions for one second and the dashboard enters from below.

Sidebar uses one tab only; desktop resizing is via the highlighted edge and is limited to 13–18%.
