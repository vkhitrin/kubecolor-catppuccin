<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/kubecolor/kubecolor">kubecolor</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/vkhitrin/kubecolor-catppuccin/stargazers"><img src="https://img.shields.io/github/stars/vkhitrin/kubecolor-catpuccin?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/vkhitrin/kubecolor-catppuccin/issues"><img src="https://img.shields.io/github/issues/vkhitrin/kubecolor-catpuccin?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/vkhitrin/kubecolor-catppuccin/contributors"><img src="https://img.shields.io/github/contributors/vkhitrin/kubecolor-catpuccin?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Adding The Themes

1. Download theme file(s):

```bash
wget -P "/tmp/" https://github.com/vkhitrin/kubecolor-catppuccin/raw/main/catppuccin-latte.yaml
wget -P "/tmp/" https://github.com/vkhitrin/kubecolor-catppuccin/raw/main/catppuccin-frappe.yaml
wget -P "/tmp/" https://github.com/vkhitrin/kubecolor-catppuccin/raw/main/catppuccin-macchiato.yaml
wget -P "/tmp/" https://github.com/vkhitrin/kubecolor-catppuccin/raw/main/catppuccin-mocha.yaml
```

2. Copy theme to `${HOME}/.kube/color.yaml` **OR** set `KUBECOLOR_CONFIG=<PATH_TO_THEME>`

```bash
cp /tmp/catppuccin-mocha.yaml ${HOME}/.kube/color.yaml # Option 1
export KUBECOLOR_CONFIG="/tmp/catppuccin-mocha.yaml" # Option 2

```
