<h1 align="center"><img src="https://raw.githubusercontent.com/daltonmenezes/electron-app/refs/heads/main/docs/images/bullet.svg" width="20" /> Theming</h1>

As the app uses [shadcn/ui](https://ui.shadcn.com/) components, theming is done following their guidelines. Check their [Theming documentation](https://ui.shadcn.com/docs/theming) for more details.

## Changing the default theme
By default, the app uses the `dark` theme, you can change it by modifying the `class` attribute in the `html` tag in the `src/renderer/index.html` file:

```html
<!DOCTYPE html>
<html lang="en" class="dark">
```