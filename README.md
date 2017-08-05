# glamorous-native-orientation

A declarative orientation style addon for `glamorous-native`

## Example
```js
const OrientationThemeProvider = withOrientation(ThemeProvider)

const OrientationStyledComponent = glamorous.view(
  portraitStyle({fontSize: 24}),
  landscapeStyle({fontSize: 36})
)

...

<OrientationThemeProvider>
  <OrientationStyledComponent>
    {`I'm large on landscape, and small on portrait`}
  </OrientationStyledComponent>
</OrientationThemeProvider>
```
