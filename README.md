# Scooby-Doo Flash Games Archive

Welcome to the **Scooby-Doo Flash Games Archive**, a simple web project aimed at preserving classic, abandoned browser games using the Ruffle emulator.

**Play the games live here:** [https://tanehans.github.io/scooby-doo-flash-archive/](https://tanehans.github.io/scooby-doo-flash-archive/)

## About This Project

This site makes use of the powerful [Ruffle emulator](https://ruffle.rs/) to allow these old `.swf` Flash games to be played smoothly right in your modern browser, without any need for plugins or outdated software.

## The Games

The original game `.swf` files are preserved and included in this repository. If you are looking to download the raw SWF files for your own archival purposes, you can find them organized inside the `games/` folder of this project:

- `games/mayan-mayhem/`
- `games/haunts-for-the-holidays/`
- `games/high-seas/`

Feel free to download the original Flash files to use in standalone emulators or desktop players of your choice!

## Running Locally

To run this archive locally, you can start a simple HTTP server in the root of the repository:

```bash
python -m http.server 8080
```

Then, navigate to `http://localhost:8080/` in your browser.
