# sketchthat.com Static HTML Website

## Build

The build script will wrap up the CSS, Images & HTML - minify/uglify where appropriate and copy it to the `./dist` folder.

```
npm run build
```

## Deploy

Firebase is used to host `sketchthat.com`.

```
firebase deploy --only hosting
```

## Circle CI

When commiting changes to `GitHub` the `CircleCI` script will run and auto-build & deploy to Firebase.
