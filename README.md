# Friendly Eats Extended Codelab

This is the source code that accompanies the
[Firestore Extended iOS Codelab](https://codelabs.developers.google.com/codelabs/firebase-cloud-firestore-workshop-swift).

The codelab will walk you through developing a more fully-featured restaurant
recommendation app powered by Cloud Firestore on iOS.

If you don't want to do the codelab and would rather view the completed sample
code, see the `codelab-complete` branch.

## 201908 Update

Error: Cloud function needs to be called with an event parameter.

https://stackoverflow.com/questions/51675979/why-would-a-firebase-background-function-on-node-js-8-complain-about-an-event-pa

_package.json_
```
"engines": {
    "node": "8"
  },
  "dependencies": {
    "firebase-admin": "^5.13.0",
    "firebase-functions": "^2.0.0"
  },
```