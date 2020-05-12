---
id: Themes
title: Themes
---

By default there will be two different app themes provided in the dating app settings:-
* lightTheme
* darkTheme

## Accessing Themes
Open the config folder present in the root directory to access the themes file.

```
cd config
touch themes.ts
```

```
export const darkTheme: AppTheme = {
    backgroundColor: "#000000",
    highlightColor: "grey",
    highlightTextColor: "#ffffff",
    textColor: "#fff",
    lightTextColor: "#b3b3b3",
    lightBottomColor: "#666666",
    profileColor: '#f5f5f5',
    profileTextColor: '#959595',
    profilePlaceholder: '#c4c4c4',
    alternateMessageBackgroundColor: '#4682b4',
    appColor: '#fd7c62',
    facebookColor: '#39579a',
    googleColor: '#e3384c',
    twitterColor: '#00acee',
    inputColor: "#aaaaaa",
    inputBorderColor: "#dadada",
    errorColor: '#FF0000',
    forgetColor: '#fd8f90',
    premiumColor: '#7b7b7b',
    notifyColor: '#fb3f5f',
    successColor: '#2bb773',
}
  
export const lightTheme: AppTheme = {
    backgroundColor: "#ffffff",
    highlightColor: "green",
    highlightTextColor: "#ffffff",
    textColor: "#333",
    lightTextColor: "#b3b3b3",
    lightBottomColor: "#e6e6e6",
    profileColor: '#f5f5f5',
    profileTextColor: '#959595',
    profilePlaceholder: '#c4c4c4',
    alternateMessageBackgroundColor: '#B0E0E6',
    appColor: '#fd7c62',
    facebookColor: '#39579a',
    googleColor: '#e3384c',
    twitterColor: '#00acee',
    inputColor: "#aaaaaa",
    inputBorderColor: "#dadada",
    errorColor: '#FF0000',
    forgetColor: '#fd8f90',
    premiumColor: '#7b7b7b',
    notifyColor: '#fb3f5f',
    successColor: '#2bb773',
}
```

You can change the predefined values or text according to your requirements.
If you need to add more themes in the app just define the theme name & various style properties in the above mentioned file.
