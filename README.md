# Hosting error

## Install

```bash
git clone git@github.com:istarkov/firebase-hosting-error.git
cd firebase-hosting-error
yarn
```

set your project [here](https://github.com/istarkov/firebase-hosting-error/blob/master/.firebaserc#L3)

run

```shell
firebase use {YOUR_PROJECT}
firebase deploy
```

open https://{YOUR_PROJECT}.firebaseapp.com and you will see an error

**Error: Forbidden**
**Your client does not have permission to get URL /helloWorld/ from this server.**

If you will remove [region](https://github.com/istarkov/firebase-hosting-error/blob/master/functions/index.js#L4)
so defult will be used, all will be fine.
