---
authorinformation:
  - null
  - Pieterjan Vandenweghe
keyword: null
---

# Manifest properties

| Property | Description |
| :--- | :--- |
| `short_name` and/or `name` | You must provide at least the `short_name` or `name` property. If both are provided, `short_name` is used on the user's home screen, launcher, or other places where space may be limited. `name` is used when the app is installed. |

\| \|`icons`\|When a user installs your PWA, you can define a set of icons for the browser to use on the home screen, app launcher, task switcher, splash screen, and so on.

The `icons` property is an array of image objects. Each object must include the `src`, a `sizes` property, and the `type` of image.

\| \|`start_url`\|Tells the browser where your application should start when it is launched, and prevents the app from starting on whatever page the user was on when they added your app to their home screen.Your `start_url` should direct the user straight into your app, rather than a product landing page. Think about what the user will want to do once they open your app, and place them there.

\| \|background\_color\|Used on the splash screen when the application is first launched on mobile.

\| \|display\|You can customize what browser UI is shown when your app is launched. For example, you can hide the address bar and browser chrome. Games can even be made to launch full screen.

\|

[1](re_manifest_properties.md#fnsrc_1) [https://web.dev/add-manifest/](https://web.dev/add-manifest/)

