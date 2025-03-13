# minimal-expo-router-error

This repository is intended to be a minimal reproducible code for the build error using yarn and `expo router 52.0.38`

Notice that you should be using **node version 18.18.0** as it's the version that runs on the expo build environment.

The error in question is the following

```
error undici@7.5.0: The engine "node" is incompatible with this module. Expected version ">=20.18.1". Got "18.18.0"
error Found incompatible module.
```

## Steps to reproduce

- Run `yarn install`