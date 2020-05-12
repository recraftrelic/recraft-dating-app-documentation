---
id: Constants
title: Constants
---

By using constants you can easily manage & access the static values or items throughout the app.

## Accessing Constants
Open the config folder present in the root directory to access the constants file.

```
cd config
touch DefaultConfig.ts
```

```
// @ts-ignore
const Logo = require("../images/logo.png")

export const defaultConfig: ApplicationConfig = {
    constants: {
      selectedTheme: ThemeKey.light,
      selectedLanguage: LanguageKey.en,
      title: "RECRAFT DATING",
      recraftLogo: Logo,
    }
}
```

As you can see there are various predefined constants in the above mentioned file. You can add more constants to use in the dating app.
