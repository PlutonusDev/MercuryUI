<div align="center">
    <br />
    <p>
        <h1><strong>MercuryUI</strong> for Roblox</h1>
        <img src="https://img.shields.io/github/stars/PlutonusDev/MercuryUI.svg">
        <img src="https://img.shields.io/github/last-commit/PlutonusDev/MercuryUI.svg">
        <img src="http://hits.dwyl.io/PlutonusDev/MercuryUI.svg">
        <img src="https://github-size-badge.herokuapp.com/PlutonusDev/MercuryUI.svg">
        <img src="https://david-dm.org/PlutonusDev/MercuryUI/status.svg">

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
</p>
</div>

---

## How to Utilize MercuryUI

Adding MercuryUI to your project is simple, simply add the following line to either the **top** of your script, or **before** any `Mercury` functions are called.

```lua
loadstring(game:GetService("HttpService"):GetAsync("https://raw.githubusercontent.com/PlutonusDev/MercuryUI/master/MercuryUI.lua"))()
```

After that, you can create a new window with `Mercury.Window.new()` along with a few variables, if you so choose.
```lua
local window = Mercury.Window.new({
    title = "Hello, world!",
    font = "milkshake", -- Only "milkshake" is implemented.
    dim = {
        xloc = 0.5,     -- Location{ScalarX}
        yloc = 0.5,     -- Location{ScalarY}
        xlen = 0.6,     -- Size{ScalarX}
        ylen = 0.6,     -- Size{ScalarY}
        border = 2      -- BorderSizePixel{int} or false
    },
    color = {
        background = Color3.FromRGB(50, 50,50),
        accent = Color3.fromRGB(30, 30, 30),
        border = Color3.fromRGB(255, 255, 255),
        title = Color3.fromRGB(100, 220, 230),
        label = Color3.fromRGB(230, 230, 230)
    }
})
```
And with that, you have yourself a window.

> ***! More docs will be added later***

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://plutonus.codes/"><img src="https://avatars3.githubusercontent.com/u/46195982?v=4" width="100px;" alt=""/><br /><sub><b>Joshua Hughes</b></sub></a><br /><a href="https://github.com/PlutonusDev/MercuryUI/commits?author=PlutonusDev" title="Code">💻</a> <a href="#plugin-PlutonusDev" title="Plugin/utility libraries">🔌</a> <a href="#maintenance-PlutonusDev" title="Maintenance">🚧</a> <a href="https://github.com/PlutonusDev/MercuryUI/commits?author=PlutonusDev" title="Tests">⚠️</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!