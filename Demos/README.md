# Pluralsight - Node.js: Deploying Applications Course - Module 1

This code was captured as the end state of Module 1 of the Pluralsight course [Node.js: Deploying Applications](https://app.pluralsight.com/library/courses/nodejs-deploying-applications)

## Steps to run

1. Create `.env` file in the `src` directory.
2. Add `APP_DEBUG=1` to the `.env` file.
3. Run `npm install`
4. Running at least Node v22.7.0, run this command from the root directory to start the application: `node --env-file=src/.env --experimental-sqlite src/app.mjs`.
