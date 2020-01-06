# SeparateRecords / rob.ac

My personal landing page.

I took a while to do this because I wanted to do it right, with native support for dark/light modes, reduced motion, and different screen sizes.

## Developing

1. `npm install` to install the dependencies.
2. `npm run dev` for server with live reloading (or `npm run build` for a single build)

### Project structure

Files under `css/` are generated by the build script, which compiles the files in `src/scss`.

The live server (`npm run server` or `npm run dev`) ignores all files that are not `index.html` or files in `css/`.
