<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/MrRio/vtop/">vtop</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/vtop/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/vtop?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/vtop/issues"><img src="https://img.shields.io/github/issues/catppuccin/vtop?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/vtop/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/vtop?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="./assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="./assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="./assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="./assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="./assets/mocha.webp"/>
</details>

## Usage

1. Download the flavor with the accent of your choice from `themes/<flavor>/catppuccin-<flavor>-<accent>.json`.
2. Copy the file into your vtop themes directory `<Global node modules directory>/vtop/themes`, you can find your **Global node modules directory** by running `npm root -g`
3. Run vtop and load the custom theme: `vtop --theme catppuccin-<flavor>-<accent>`

<!-- The FAQ section is optional. Remove if needed.-->
## 🙋 FAQ

- Q: **_"How can I make this the default theme?"_**\
  A: Add this line into your `.bashrc`/`.zshrc`:

  ```bash
  alias vtop="vtop --theme catppuccin-<flavor>-<accent>"
  ```

## Building the themes

Catppuccin for Vtop uses [Whiskers](https://github.com/catppuccin/whiskers).

Modify the themes by editing [vtop.tera](./vtop.tera), then run `whiskers vtop.tera`.

## 💝 Thanks to

- [AlwaysNur](https://github.com/alwaysnur)
- [uncenter](https://github.com/uncenter)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
