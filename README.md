# Firebase recommended template

This repository is the recommended template for developing with Firebase.  
It has a very simple and minimum directory structure, and ready to deploy and test.  
You don't have to run `firebase init` anymore.

## How to setup your project

- Create your repository from this template. Please click "Use this template".
  - See more: [Creating a repository from a template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
- Run `yarn install` to install dependencies.
- Open `.firebaserc` and change `<your firebase project id>` to your firebase project id.
- [Optional] Add alias(es) to `.firebaserc` (e.g. "dev", "prod").
- [Optional] Write or copy `firestore.rules`, `storage.rules`, `firestore.indexes.json` if needed.
- [Optional] Execute `yarn firebase login` if you haven't logged in yet.
- Have a good development 🔥🔥🔥.

## Details

- Node version: 8 (v8.16.2 is recommended).
- Source directory:`src/`
- Deploy directory: `dist/`
- Hosting files directory: `public/`
- Test directory: `test`
- `firestore.rules`, `storage.rules`, and `firestore.indexes.json` are initial state.
- The following is the list of prepared script commands:

```
- build: Build `src` directory.
- serve: Launch functions emulator.
- shell: Launch functions shell.
- deploy: Deploy to Firebase project.
- logs: Print function's logs.
- test-rules: Run test of `firestore.rules`.
```

## `npm`

If you want to use `npm` instead of `yarn`, please replace `yarn` to `npm` in `package.json`.
