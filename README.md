# forge-offline-pdf-edit2D

using Forge Viewer API with offline capabilities. This is testing the edit2D extension and calculating the length og polygons.

offline-pdf-markup DEMO: [https://elated-brown-a54e18.netlify.app/](https://elated-brown-a54e18.netlify.app/)

Piggybacking off this demo to get the pdfs into forge but this code is using Edit2D
Blog post: [https://forge.autodesk.com/blog/fast-pdf-viewingmarkup-inside-forge-viewer](https://forge.autodesk.com/blog/fast-pdf-viewingmarkup-inside-forge-viewer)

# Running project

Since the files are static you need to serve them from a server if you encounter CORS policy in your browser.
Below is one example, you can use any server you'd like to serve the files.

Install Node.js and use the package manager [NPM](https://www.npmjs.com/) to install http-server.

CD into the the directory and run the command below to serve the files in docs

```bash
npx http-server ./docs
```
