# Boilerplate Marvin Plugin

Create a plugin is very much simple. It is necessary understand [how the syntax works](https://github.com/marvin-js/marvin/blob/master/docs/how-is-syntax.md).

Example of plugin:

```javascript
module.exports = function (opts, params1, params2) {
  //... make something with the params & options
}
```

The plugin can return a Object/Promise.

## Recommendation for name of package

Marvin searching the plugins with prefix `marvin-plugin-`.

**Example:**

```
marvin-plugin-<name>
```
