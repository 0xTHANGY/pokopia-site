# Pokopia Habitat Helper

A single-file web app for browsing Pokopia habitats and Pokémon, planning habitats on in-game maps, and tracking your progress. The interface is in Chinese.

This is an unofficial fan tool with no affiliation with Nintendo or The Pokémon Company. Third-party game content, sprites, maps, and other assets belong to their respective owners. The MIT license applies to the app code. Third-party assets retain their respective rights.

[Live demo](https://pokopia-habitat-helper.surge.sh)

## Run locally

Open `index.html` in a browser, or run this command from the repository root and open `http://localhost:8000`.

```sh
python3 -m http.server
```

The app uses vanilla HTML, CSS, and JavaScript in one file, with no build step or software dependencies. It stores progress and custom map data in the browser's `localStorage`.
