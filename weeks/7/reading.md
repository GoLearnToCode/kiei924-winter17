# Getting Started With Firebase

If you don't already have one, set-up an account at firebase.google.com and install the Firebase command-line tools using:

```
npm install -g firebase-tools
```

If you're on Mac, you might get a bunch of "permission denied" errors when installing. If this happens, try installing with `sudo`, like this:

```
sudo npm install -g firebase-tools
```

## Firebase Database Setup

1. In the Firebase console, under "Database", select the tab that says "Rules"
2. Change the part that reads `"auth != null"` to `true` and hit "Publish". The finished rules should look like this:

```
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```

## Firebase Hosting Setup

1. `cd` into your project.
2. Build the production code for your application from the command-line, using `npm run build`.
3. Run `firebase init` - unselect "Database" and, when prompted for a location for the public directory, type `build`. Accept all other defaults, by simply pressing enter.
4. `firebase deploy`

Every time your code is changed, and you want to deploy to Firebase again, simply `npm run build` and `firebase deploy` again.
