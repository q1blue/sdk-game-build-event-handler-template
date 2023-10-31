# Netlify SDK Build Event Handler template

This is a template to show you how a Build Event Handler can be made using the Netlify SDK.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/integration/start/deploy?repository=https://github.com/netlify/sdk-build-event-handler-template&integrationName=build-event-handler-template&integrationSlug=build-event-handler-template&integrationDescription=Build%20Event%20Handler%20Template&scopes=site:read&integrationLevel=site)

## Scripts

### Build

This builds the integration and puts it into the `.ntli` folder. This is the folder that Netlify uses to run the integration.

```bash
npm run build
```

### Dev

This bundles your integration code and starts a local GraphQL server for any Connectors you have defined. This is useful for testing your integration locally.

```bash
npm run dev
```

### Preview

This bundles your integration code and starts a preview server. This is useful for previewing your integration UI locally.

```bash
npm run preview
```
