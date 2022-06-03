# GeckoCo Site

### Running locally
```
npm install

npm start
```

### Test a production build locally
```
npm run dist
```

Site will be served locally from `localhost:3000`

Note that `SITE_ROOT` env variable should be available when on deployment environment (e.g `https://www.<hostname>`).

`SITE_RECAPTCHA_KEY` will also need to be available for the form recaptcha to be active. See [the API docs](https://www.google.com/recaptcha/admin/create) for this.
