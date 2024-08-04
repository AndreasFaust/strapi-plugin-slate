# Strapi Plugin Slate

This plugin has the single purpose to replace Strapi’s default Slate implementation, because it does not keep formatting after pasting from Rich Text or Google Docs.

This plugin is identical to this pull request:
https://github.com/strapi/strapi/pull/20262

```bash
npm i strapi-plugin-slate
```

```js
// config/plugins.js
module.exports = () => ({
  slate: {
    enabled: true,
  },
});
```
