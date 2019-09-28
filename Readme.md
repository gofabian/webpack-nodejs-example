
# Run during development

Install dependencies from package-lock.json:

    $ npm ci

Start application at ./src/main.js

    $ npm start


# Build bundle

Install dependencies from package-lock.json:

    $ npm ci

Bundle code from ./src to ./dist/bundle.js:

    $ npm run build

Remove dev-dependencies for deployment:

    $ npm ci --only=production

Optionally check whether bundle works as expected:

    $ npm run start-build


# Deploy build result

Deploy the following build artifacts:

- application: ./dist
- dependencies: ./node_modules
