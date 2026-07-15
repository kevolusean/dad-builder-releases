# DaD Builder — Releases

Download the latest build of the Dark and Darker character builder app from the [Releases](../../releases) page.

Each release is a standalone zip of the built app — no build step, no install, just unzip and run.

**Prerequisite**: [Node.js](https://nodejs.org) must be installed (any recent version) — the launchers use it to serve the app locally. If you don't have it, install Node first, then come back here.

## How to run it

1. Download the `.zip` from the latest [release](../../releases).
2. Unzip it anywhere.
3. Launch it for your OS:

### Windows
Double-click **`DaD_Builder.cmd`**. It starts a local server and opens the app in your browser automatically at `http://localhost:3000`.

### macOS / Linux
Open a terminal in the unzipped folder and run:
```
./serve.sh
```
If you get a "permission denied" error, run `chmod +x serve.sh` once, then try again. Then open `http://localhost:3000` in your browser.

If `./serve.sh` doesn't work for any reason, you can always run the underlying command directly from that folder:
```
npx serve dist -l 3000
```

## Stopping the server
Close the terminal window / `.cmd` window, or press `Ctrl+C` in it.

---
This repo holds built releases only. Source code lives in a private repo.
