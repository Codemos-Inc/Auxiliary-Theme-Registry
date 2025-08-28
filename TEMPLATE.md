# \<registry-name\>

This is a community auxiliary theme registry from \<owner\>.

### 🔗 Compatibility

The table below showcases the compatibility between different distributions of this registry and their respective supported distributions of [Codemos Modern](https://github.com/EmrecanKaracayir/Codemos-Modern).

| Registry Distribution  | Supported CM Distribution |
| ---------------------- | ------------------------- |
| \<lower\>...\<higher\> | \<lower\>...\<higher\>    |

    Check official registry's readme for an example.

### 🎯 Target

    Explain registry's general purpose and direction. What can subscribers expect from it? Who can subscribe?

### ❤️ Subscription

Add the following entry to your `settings.json` file.

    Change the "<owner>/<repo>" value below to your registry's relative path.

```jsonc
{ // settings.json
  "codemosModern.auxiliaryThemeRegistries": [
    // ...
    "<owner>/<repo>",
    // ...
  ]
}
```

### 🎨 Catalog

    You can either list your catalog or use the template's explanation below.

Individual publishers & themes are listed in the `index.json` file at the root of this repository. You can find the list of themes in the `themes` property of the `index.json` file. Each theme is represented by an object with the following properties.

- **Publisher:** The publisher of the theme.
- **Extension:** The name of the extension containing the themes.
- **Theme:** The name of the theme.
- **Origin:** The origin of the theme.
- **License:** The license of the theme.

### 📋 Change Log

    Explain your latest update. Either major or each update can be explained.

### 🙌🏼 Contribution

    Explain to users if and how they can contribute to this registry.

### 📜 License

    Give users the information about the license of this repository.
