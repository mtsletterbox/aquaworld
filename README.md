# Underwater World

A lightweight animated aquarium built with plain HTML, CSS, and the Canvas 2D API. The scene includes swimming fish, waving seaweed, bubbles, light rays, and a sandy seabed. No build tools, packages, or external assets are required.

## Run locally

Open `index.html` in a modern browser. To serve it locally instead, run this command from the repository directory:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Interact

- Click or tap the scene to release bubbles and food; nearby fish will swim toward the food.
- Select **New World** to regenerate the aquarium.
- Resize the browser window to fit the scene to the new viewport.

## Project structure

```text
.
├── index.html   # Complete self-contained aquarium experience
└── README.md    # Project overview and usage instructions
```

## Development notes

The application is intentionally dependency-free and implemented in `index.html`. It uses `requestAnimationFrame` for animation, pointer events for mouse and touch interaction, and device-pixel-ratio-aware canvas sizing. Edit the HTML, CSS, or inline JavaScript directly, then refresh the browser to see changes.

There is currently no automated test suite or build pipeline. Please manually verify the page in a modern browser after making changes, including pointer interaction and window resizing.

## License

No license file is currently included. Unless a license is added, the repository does not explicitly grant permission to reuse or redistribute the code.
