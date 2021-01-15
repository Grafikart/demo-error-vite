## Vite bug demo project

1 - `yarn`

2 - Start the vite dev server `yarn dev`

3 - While the dev server is runing run `yarn serve` that will simulate our second app loading vite assets

http://localhost:3000 shows a page with the logo but
http://localhost:8000 shows a page without the logo.

The style is injected and the image path is now looked from the server instead of being reached from the vite dev server
