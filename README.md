# express
- hints
- run `npm install`
  - `package.json` needs to be present in the image
  - the image must have `nodejs` installed
- run `node server.js`
  - `server.js` needs to be present in the image
  - the image must have `nodejs` installed

## run the image as a container
- docker run -d -p 3000:3000 kw2mo/hello-world
  - replace kw2mo/hello-world with your student id and image name
