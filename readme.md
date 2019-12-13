<div align="center">
    <br />
    <p>
    <h1><strong>MercuryUI</strong> for Roblox</h1>
    <img src="https://img.shields.io/github/stars/PlutonusDev/MercuryUI.svg">
        <img src="https://img.shields.io/github/last-commit/PlutonusDev/MercuryUI.svg">
    </p>
    <img src="http://hits.dwyl.io/PlutonusDev/MercuryUI.svg">
    <img src="https://github-size-badge.herokuapp.com/PlutonusDev/MercuryUI.svg">
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